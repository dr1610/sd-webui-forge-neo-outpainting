# sd-webui-forge-neo-outpainting

Outpainting scripts for Stable Diffusion WebUI Forge - Neo.

This repository redistributes the classic WebUI outpainting scripts for users who want the `img2img` script dropdown entries in Forge - Neo:

- `Poor man's outpainting`
- `Outpainting mk2`

## Installation

Copy the Python files from this repository's `scripts` folder into your Forge - Neo `scripts` folder.

For a Stability Matrix install, the destination is usually:

```text
Data/Packages/Stable Diffusion WebUI Forge - Neo/scripts/
```

Then restart Forge - Neo. The scripts should appear in the `img2img` script dropdown.

## Files

```text
scripts/
  poor_mans_outpainting.py
  outpainting_mk_2.py
```

## Credits

These scripts are from the Stable Diffusion WebUI family and were taken from:

- https://github.com/Panchovix/stable-diffusion-webui-reForge
- https://github.com/AUTOMATIC1111/stable-diffusion-webui

`outpainting_mk_2.py` also contains code credited in-source to:

- https://github.com/parlance-zz/g-diffuser-bot

## License

AGPL-3.0. See [LICENSE](LICENSE).
