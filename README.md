# Docker Volume Renamer

This tool is a Bash script designed to facilitate the renaming of Docker volumes. It automates the process of creating a new volume, copying data from the existing volume to the new one, and then removing the old volume.

## Created with ChatGPT

The creation of this tool was assisted by ChatGPT, leveraging its AI capabilities to generate the necessary Bash scripts and instructions. The conversation is available [here](https://chat.openai.com/share/d011e8f1-b986-483e-b53d-d8ad26518f3d).

## Author

Kevin Veen-Birkenbach  
Email: kevin@veen.world  
Website: [https://www.veen.world/](https://www.veen.world/)

## Usage

To use this tool, simply execute the Bash script with the old and new volume names as arguments:

```bash
./rename_docker_volume.sh old_volume_name new_volume_name
```

Ensure you have a backup of your data before running this script to avoid data loss.

## License

This repository is under the GNU AFFERO GENERAL PUBLIC LICENSE, Version 3, dated 19 November 2007. Please see the `LICENSE` file for the full text of the license.

## Contributions

Contributions are welcome. Please feel free to submit pull requests or create issues for any bugs or enhancements.

## Disclaimer

This tool is provided "as is", without warranty of any kind. Use at your own risk.
