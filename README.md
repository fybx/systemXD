<picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/fybx/systemXD/main/icons/light.svg">
    <source media="(prefers-color-scheme): light" srcset="https://raw.githubusercontent.com/fybx/systemXD/main/icons/dark.svg">
    <img alt="The systemXD logo." src="https://raw.githubusercontent.com/fybx/systemXD/main/icons/light.svg" width="500">
</picture>

---

# systemxd (stylized systemXD as in XD)

systemXD is a WIP "service" abstraction layer, built to be used along systemd timers and services. systemXD can 
- build services using custom scripts, 
- update: 
  - artifacts (built and deployed services)
  - configurations (consumed by services)
- deploy systemd services and timers, 
- insert secrets to any step from building to deploying,
- receive streams (logs, metrics, etc.) and feed them into other services (natively, [systemxd-frontend][0]).

## Contributing

I welcome contributions to enhance and improve this project! Whether you want to fix a bug, add a new feature, or suggest an improvement, your contributions are highly appreciated.

Just so you know, by contributing to this project, you agree to license your contributions under the same license governing this library. If you're unsure or have questions about the contribution process, please get in touch with me by opening an issue.

> (yes, I use the same text for every project I own, I'm lazy)

## Credits

Feel free to contact me for collaboration on anything!

Ferit Yiğit BALABAN, <[fyb@fybx.dev][llmail]>

[My Website][llwebsite] • [My Bento][llbento] • [X][llx] • [LinkedIn][lllinkedin]

[0]: https://github.com/fybx/systemxd-frontend
[llmail]: mailto:fyb@fybx.dev
[llwebsite]: https://fybx.dev
[llbento]: https://bento.me/balaban
[llx]: https://x.com/fybalaban
[lllinkedin]: https://linkedin.com/in/fybx
