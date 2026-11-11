> **CultureReset fork of [cloudflare/foundations](https://github.com/cloudflare/foundations).** Cloudflare's Rust service foundations library.
>
> - **Why it is here:** Saved for reference.
> - **Does anything run from it:** No.
> - **Changes:** The default branch has no CultureReset commits; it is upstream as of the last sync.
> - **License:** BSD-3-Clause, from upstream. For updates and issues, use [upstream](https://github.com/cloudflare/foundations).
>
> The upstream README follows unchanged.

---

# Foundations

<p align="center">
    <a href="https://github.com/cloudflare/foundations">
        <img src="media/banner.png" alt="banner" style="width:472px; height: 375px" />
    </a>
</p>

Foundations is a modular Rust library, designed to help scale programs for distributed,
production-grade systems. It enables engineers to concentrate on the core business logic
of their services, rather than the intricacies of production operation setups.

If you need any of those:

* logging
* distributed tracing
* metrics
* memory profiling and [jemalloc](https://github.com/jemalloc/jemalloc) allocator
* security features, such as [seccomp](https://en.wikipedia.org/wiki/Seccomp)-based syscall sandboxing
* service configuration with documentation
* CLI helper that takes care of the configuration loading

then Foundations is a tool of choice for you.

## Documentation

https://docs.rs/foundations/

## Examples

https://github.com/cloudflare/foundations/tree/main/examples

## License

BSD-3 licensed. See the [LICENSE](LICENSE) file for details.