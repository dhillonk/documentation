# Getting Started with ODP

![Choose Your Path](./media/choose_path.png)

## Welcome to the Open Device Partnership (ODP)!

ODP is a community-driven framework for building **secure**, **modular**, and **reusable** firmware components across a range of systems. Whether you’re interested in low-level boot firmware, embedded controller services, or integrating a complete firmware stack, ODP has something for you.

## What is ODP?

ODP brings modern software engineering practices—like memory safety and dependency injection—to the world of firmware. It leverages Rust to improve confidence, maintainability, and modularity across diverse hardware and system designs.

It also embraces existing standards like UEFI, DICE, ACPI, and EC protocols—but makes them more accessible and safer to implement.

---

## How to Use This Guide
This documentation is designed to serve multiple audiences working with the Open Device Partnership (ODP). Whether you're a firmware engineer, technology advisor, integrator, or contributor, you'll find resources tailored to your needs.

### Role-Based Reading Guidance

|   Role            | Recommended Path                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| __Firmware Engineer__ | Follow the documentation from start to finish. Includes technical tutorials, architectural insights, and integration exercises. |
| __Technology Advisor__ | Read the mainline content through the [Architecture Overview](../architecture/architecture.md), skipping hands-on exercises as needed. |
| __Integrator__        | Read the [Architecture Overview](../architecture/architecture.md), then use [What is in ODP?](../what/what.md) to find the relevant implementation repositories. |
| __Contributor__       | Review the value proposition and architecture sections, then use [What is in ODP?](../what/what.md) to find the relevant project repositories. |
| __Security Reviewer__ | Start with the [Security Model](../architecture/security_architecture.md) and [Firmware Updates](../architecture/secure_firmware_updates.md). |
| __Patina SDK (UEFI) Developer__ | Refer to external Patina resources: the [Patina Book](https://opendevicepartnership.github.io/patina/) for guides and concepts, and the [Patina source repository](https://github.com/opendevicepartnership/patina) for crates, code examples, and implementation notes. |  


---

### Where to next?

If you are not a developer, you can skip the next section and continue to
[What is in ODP?](../what/what.md). However, even non-developers may find it
useful to understand the basics of Rust and how ODP uses it to ensure safety
and reliability in firmware development.
