<p align="center">
  <picture>
    <!-- <source media="(prefers-color-scheme: dark)" srcset="./dark.png"> -->
    <img alt="Text changing depending on mode. Light: 'So light!' Dark: 'So dark!'" src="/assets/logo_symbol_light.svg" width="200">
  </picture>
</p>

## prefix.dev – blazing fast package management

At [`prefix.dev`](https://prefix.dev) we are commited to a great developer experience, fast and reproducible software environments and speedy software package management that gets you and your colleagues ready to develop right away!

We are the people behind the succesful [`mamba`](https://github.com/mamba-org) package manager. Mamba handles packages for Python, C, C++, Fortran, Ruby and many more programming languages – at prefix.dev we are commited to take what we've learned and improve on that.

Our main projects are:
- `pixi`: The new package manager that can handle `conda` and `pypi` packages to create software environments in a modern way.
- `rattler-build`: The conda-package builder, as a replacement for `conda-build` and `boa`, to significantly speed up conda package creation.
- `rattler`: Rust crates to work with the Conda ecosystem. (`conda` is `python` and `mamba` is `C++`)
- `rip`: Rust crates to work with the `pypi` ecosystem. 
- [prefix.dev](https://prefix.dev/channels): The fast conda package index, and private channel hosting server.

We stand for:

- **Package management should be cross-platform** – we support Linux, macOS and Windows and WebAssembly natively.
- **Ship _binary_ packages** - Shipping packages as source to then compile is a way to slow down users of your code, we make building binary packages as easy as possible so you only build them once!
- **We write our code in Rust**, because it is extremely developer friendly, perfect for our use case (low level, high computational load), cross platoform, and it has an amazing open source community which provides tons of great libraries like Serde, Miette, Reqwest, etc.


We collaborate with the open source [`conda-forge`](https://conda-forge.org) package distribution that ships many tens of thousands of software packages for data science, machine learning. You can browse all available packages on [prefix.dev](https://prefix.dev)! If you are missing a package, do not hesitate to reach out to us [via email](mailto:hi@prefix.dev) and we can help.

[**For more, read our blog posts**](https://prefix.dev/blog).
