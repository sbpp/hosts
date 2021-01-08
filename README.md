# Hosts
A list of known-good hosts to run SourceBans++ on.<br/>
**NOTE**: This list will focus on hosting the SourceBans++ Web panel and/or a MySQL database not gameserver hosts!

---
## Table of contents
1. [Hosts](#hosts)
2. [Contributing](#contributing)
3. [License](#license)

---
## Hosts
| Name | Minimal plan | Type | Data center locations | Trial | Free | Ideal for |
|:----:|:------------:|:----:|:---------------------:|:-----:|:----:|:---------:|
| [Hetzner VPS](https://www.hetzner.com/cloud) | [See Pricing](https://www.hetzner.com/cloud#pricing)<br/> (2.49 €/mo) | VPS | Germany<br/> Finland | No | No | Webserver<br/> MySQL database|
| [NFO Servers](https://www.nfoservers.com) | [See Pricing](https://www.nfoservers.com/order-virtual-dedicated-server.php)<br/> (9.99 US$/mo) | VPS | USA<br/>Germany | Yes, 2 days | No | Gameserver<br/>Webserver<br/>MySQL database|

---
## Contributing
Do you want to contribute? Awesome!\
Just fork this repo, add your host and open a PR. (or [Create a new Issue](https://github.com/sbpp/hosts/issues/new/choose))

Here is a helpful list of all the table fields with a short explanation:
|Field|Explanation|
|-|-|
|Name|Name of the host and direct link to their website (no referral links!). <br/>If the host offers multiple hosting types (e.g VPS and Managed) split them up into multiple entries and include the hosting type as a suffix.<br/><br/> (Example: Your host is named `Hetzner` and they offer `VPS` and `Managed` hosting services. You would create to entries in the table named `Hetzner VPS` and `Hetzner Managed`)|
|Minimal plan| The cheapest available hosting option.<br/> Ideally prices should be per **month (/mo)** or **year (/yr)**, but per **hour (/hr)** is also fine.<br/> If your host has a pricing chart available, include a link to it.|
|Type|[Hosting type](https://en.wikipedia.org/wiki/Web_hosting_service#Types_of_hosting)<br/><br/> Common types are: <br/> Shared<br/> VPS (Virtual private server) <br/> Dedicated<br/> Cloud<br/> Managed<br/> or Colocation|
|Data center locations|Data center locations your host is offering. (e.g Germany, Finland or US-West, EU-Central, etc.)|
|Trial|Is your host offering a trial? If yes, then include a link (no referral link!)|
|Free|Is your host offering a free hosting tier? If yes, then include a link (no referral link!)|
|Ideal for|SourceBans++ currently needs 3 different services to run:<br/> a **Webserver** for hosting the webpanel<br/> a **MySQL Database** to store data<br/> and a **Gameserver** to run the sourcemod plugins.<br/>Not every host / hosting type is ideal for running each of these services, so you should include which services run on the particular host + hosting type option. (Please only use the keywords **Webserver**, **MySQL Database** and **Gameserver**)<br/><br/>(Example: a VPS should normally be able to run the `Webserver` and a `MySQL Database`, but might not be powerful enough for a `gameserver`. A `webhost` could only run the `webpanel` and a `Dedicated` server, given the correct specs, could run all services on one machine.)|
---

## License
Distributed under the MIT License. See [`LICENSE`](LICENSE) for more information.
