# Spoofy

[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![forthebadge](https://forthebadge.com/images/badges/contains-tasty-spaghetti-code.svg)](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.thewholesomedish.com%2Fspaghetti%2F&psig=AOvVaw3OneeN_AB3XxZzgCPPTtfv&ust=1614550372646000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCJjQwf2Ki-8CFQAAAAAdAAAAABAD)
[![forthebadge](https://forthebadge.com/images/badges/it-works-why.svg)](https://www.youtube.com/watch?v=kyti25ol438)

`Spoofy` is a program that checks if a list of domains can be spoofed based on SPF and DMARC records. 


## Usage and Examples

`Spoofy` requires **Python 3+**. Python 2 is not supported. Usage is shown below:

```console
Usage:
    ./spoofy.py -d [DOMAIN]
    OR
    ./spoofy.py  -iL [DOMAIN_LIST]
```

## Domain are spoofable if the following conditions are met:
<CHART>


## Disclaimer

> This tool is only for testing and academic purposes and can only be used where
> strict consent has been given. Do not use it for illegal purposes! It is the
> end user’s responsibility to obey all applicable local, state and federal laws.
> Developers assume no liability and are not responsible for any misuse or damage
> caused by this tool and software.

## Credit

Tool was heavily inspired by [Bishop Fox's](https://github.com/BishopFox/) project called [spoofcheck](https://github.com/BishopFox/spoofcheck/).
Also big thank you to Calamity for the dmarc and spf insights!

## License

This project is licensed under the GPLv3 License - see the [LICENSE](LICENSE)
file for details
