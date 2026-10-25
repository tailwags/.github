<div align="center">
  <img src="https://raw.githubusercontent.com/tailwags/.github/main/profile/assets/tailwags.png" width="128" alt="Tailwags logo" />
  <h1>Tailwags Technology</h1>
</div>

Tailwags is a collection of systems software written in rust. Most of it is early and experimental.

## Main projects

- **[Bread](https://github.com/tailwags/bread)**: a small UEFI bootloader for
  Linux. It boots the kernel through the native Linux boot protocol instead of
  the EFI stub.
- **[Effie](https://github.com/tailwags/effie)**: a crate for writing UEFI
  applications that maps directly to the UEFI specification. Bread is built on
  it.
- **[Blakity](https://github.com/tailwags/blakity)**: a tiny `no_std` BLAKE3
  for small binaries such as UEFI applications.
- **[Sap](https://github.com/tailwags/sap)**: a small, zero-dependency
  command-line argument parser.
- **[Puppyutils](https://github.com/tailwags/puppyutils)**: coreutils,
  util-linux and other core utilities, aiming for small binaries. Work in
  progress.
- **[Maple](https://github.com/tailwags/maple)**: an experimental Linux
  environment you can target directly (`x86_64-linux-maple`), with its own
  crt0, libc and dynamic linker.
- **[Abus](https://github.com/tailwags/abus)**: a Tokio-native D-Bus
  implementation.

Other projects can be found in the
[repository list](https://github.com/orgs/tailwags/repositories).
