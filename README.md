## Climbing grade conversion script

Slapped this together while bored and tired of googling grade conversions. This tool converts climbing grades from Font (French) to YDS (American). It also converts bouldering grades fron Font to Hueco (V-Scale). This script is very basic and I would like to add more features as time progresses. 

Usage:
1. Make script executable by: `chmod u+x font_converter.py`
2. Run it! For example: `./font_converter.py 8a boulder`

More improvements coming, using this repo to track my progress on more features.

### TODO:
- [ ] - Add tests
- [ ] - Algorithm to convert grades instead of text files (might not be possible but owuld be cleaner)
- [ ] - Make grades convert the other way (from YDS to Font and from Hueco to Font)
- [ ] - Make into a proper wheel distribution for ease of use
- [ ] - Figure out how to package the text files so that the script can be run from anywhere, not just the dir that the project resides (This could be solved by Wheel Distribution?)
