Features
This software incorporates the following functionality:

Rusty Kaspa p2p Node
Kaspa wallet based on the Rusty Kaspa SDK
Rusty Kaspa CLI wallet
BlockDAG visualizer
Remote node connectivity
This project is built on top of and incorporates the Rusty Kaspa core framework.

This software is ideological in nature with a strong focus on architecture and decentralization. It is a unified codebase tightly coupled with the Rusty Kaspa project. Fully written in Rust, it is available as a high-performance desktop application on all major operating systems (Windows, Linux and MacOS) as well as in major web browsers. It does not rely on any JavaScript or Web frameworks, which greatly strengthens its security profile. The Web Browser extension based on this infrastructure is currently under development.

Releases
You can obtain the latest binary redistributables from the Releases page.
Building
To build this project, you need to be able to build Rusty Kaspa. If you have not built Rusty Kaspa before, please follow the Rusty Kaspa build instructions.

In addition, on linux, you need to install the following dependencies:

Ubuntu/Debian:
sudo apt-get update
sudo apt-get install libglib2.0-dev libatk1.0-dev libgtk-3-dev librust-atk-dev
Fedora:
sudo dnf install glib2-devel atk-devel gtk3-devel
Once you have Rusty Kaspa built, you will be able to build and run this project as follows:

From GitHub repository:
Running as Native App
cargo run --release
Running as Web App
cargo install trunk
trunk serve --release
Access via https://localhost:8080/

While the application is a static serve, you can not load it from the local file system due to CORS restrictions. Due to this, a web server is required. This application is designed to be built with Trunk and is served from the dist/ folder. This is a self-contained client-side application - once the application is loaded, the web server is no longer required.

Running Headless
Kaspa NG application binary can be started in 3 ways:

kaspa-ng - starts Kaspa NG in the default desktop mode
kaspa-ng --daemon [rusty-kaspa arguments] - starts Kaspa NG as a Rusty Kaspa p2p node daemon
kaspa-ng --cli - starts Kaspa NG as a Rusty Kaspa CLI wallet
If you need access to the wallet in a headless environment, you can start Kaspa NG in daemon mode and then use the CLI wallet to access the wallet.

License
Licensed under a PROPRIETARY MIT-style Open Source LICENSE with the following restrictions: You are expressly prohibited from using, adapting, or integrating this software into any cryptocurrency network or related technology other than the specified intended network for which it is developed - The Kaspa BlockDAG cryptocurrency network.

Contribution
Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, shall be licensed as above, without any additional terms or conditions.

Donations
If you are a Kaspa investor, please consider supporting this project. The funds will be used to cover operational costs and further the project's functionality.

kaspa:qq2efzv0j7vt9gz9gfq44e6ggemjvvcuewhzqpm4ekf4fs5smruvs3c8ur9rp
