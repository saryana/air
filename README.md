# Air Quality
The goal is to find and build a suitable method of monitoring indoor air quality. Why indoor air quality? You spend the most time in your home. Most places do not have any great filtration of air so you are still effected by air form outside. On top of that, without proper ventilation, thinkings like cooking and dust will accumulate. The hope is to be able to track this.
## Research
* There is far more here than I had expected. Most resources are about tracking outdoor data and making the data open source. It may not be bad to do both, super cheap indoor solution (maybe multiple) and then some sort of outdoor one.
* Most abundant sensor is Nova PM SDS011. It appears to lose accuracy in high humidity but, this is by far the most used sensor 20euro
## Links
* [hackAir](https://www.hackair.eu/tutorials/) - this has tutorials for rather cheap setup, but it is largely using hackAir platform and potentially wifi shield which contains much of the the logic to give the data to them. Doesn't appear to have offline support or local network. Project died in 2019 rip.
* [sensor.community](https://sensor.community/en/) - this was previously Luftdaten and seems to be the biggest one now? RIVM also referenced this. They have their [own guide](https://sensor.community/en/sensors/airrohr/) on getting a system up and running.
* [openSenseMap](https://opensensemap.org/) seems to be the largest platform for sharing data. hackAir appeared to send the data to here as well.
* [openAQ](https://openaq.org/#/) - appears to be one of the more serious onces, but offers much less on how to do guides, this lead to yet another NL link for tracking. openAQ also makes distinctions between lo cost and reference sensors.
* [Dutch Tracking site](https://www.luchtmeetnet.nl/) - Only for dutch government run sites and sensors.
* [Dutch Open reference](https://www.samenmetenaanluchtkwaliteit.nl/) - handy guide from big gov't talking about the open data. [Another helpful link](https://www.samenmetenaanluchtkwaliteit.nl/sensorcommunity). [Map of Netherlands](https://samenmeten.rivm.nl/dataportaal/)
* [Dutch Blogger](http://www.fam-oldenburger.nl/2018/08/11/luftdaten-info/)