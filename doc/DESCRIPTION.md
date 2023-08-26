ZeroTier Controller Web UI is a web user interface for a self-hosted ZeroTier network controller.

This project is highly inspired by [ztncui](https://github.com/key-networks/ztncui) and was developed to address the current limitations of applying the self-hosted [network controllers](https://github.com/zerotier/ZeroTierOne/tree/master/controller). Some [ztncui](https://github.com/key-networks/ztncui) problems cannot be fixed because of the core architecture of the project. ZeroUI tries to solve them and implements the following features:

- Full React-powered lightweight [SPA](https://en.wikipedia.org/wiki/Single-page_application) that brings a better user experience, and ZeroUI is mobile-friendly.
- ZeroUI has ZeroTier Central compatible API. That means you could use CLI tools and custom applications made only for ZeroTier Central to manage your networks.
- ZeroUI implements controller-specific workarounds that address some existing [issues](https://github.com/zerotier/ZeroTierOne/issues/859). ZTNCUI [does not](https://github.com/key-networks/ztncui/issues/63).
- ZeroUI is more feature complete. ZeroUI has almost all network-controller-supported features, for example, rule editor. The development process hasn't stopped, so you will enjoy new features and bug fixes shortly.
