<div align="center">
<img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Empress Insights logo" width="124"/>
<h1>Empress Insights</h1>

**Powerful. Intuitive. Simplify Data Analysis.**

![GitHub issues](https://img.shields.io/github/issues/empress-eco/insights)
![GitHub license](https://img.shields.io/github/license/empress-eco/insights)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/empress-eco/insights)
[![codecov](https://codecov.io/github/empress-eco/insights/branch/develop/graph/badge.svg?token=8ZXHCY4G9U)](https://codecov.io/github/empress-eco/insights)
[![unittests](https://github.com/empress-eco/insights/actions/workflows/server-tests.yml/badge.svg)](https://github.com/empress-eco/insights/actions/workflows/server-tests.yml)

</div>

## About Empress Insights

Empress Insights is an open-source data analysis and reporting tool that simplifies data analysis from databases. This tool provides an intuitive interface that empowers users with or without extensive SQL knowledge to generate complex reports and gain valuable insights from their data.

#### Key Features
- **Query Builder:** Create database queries with our user-friendly interface.
- **Visualizations and Dashboards:** Visualize query results with various charts and graphs. Create custom dashboards to get a comprehensive view of your data.
- **Connectivity:** Empress Insights currently supports integration with MySQL databases.

#### Built With
- [Framework](https://github.com/Empress/Empress)
- [Empress UI](https://github.com/Empress/Empress-ui)
- [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy)
- [eCharts](https://github.com/apache/echarts)
- [Pandas](https://github.com/pandas-dev/pandas)

## Getting Started

#### Prerequisites
Before you begin, ensure you have Docker, docker-compose, and git installed on your machine. Refer to the [Docker documentation](https://docs.docker.com/) for more information.

#### Installation
Use the following commands to clone the project and launch Empress Insights:

```sh
git clone https://github.com/empress-eco/insights.git
cd insights/docker
docker-compose up
```
Once the setup script creates a site, open the URL `http://insights.test:8000/insights` in your browser.

#### Local Installation
Follow these steps to set up the repository locally:

1. Install bench and set up a `Empress-bench` directory by following the [Installation Steps](https://Empressframework.com/docs/user/en/installation)
2. Start the server by running `bench start`
3. In a separate terminal window, create a new site by running `bench new-site insights.test`
4. Map your site to localhost with the command `bench --site insights.test add-to-hosts`
5. Get the Insights app. Run `bench get-app https://github.com/empress-eco/insights.git`
6. Run `bench --site insights.test install-app insights`.

Now, open the URL `http://insights.test:8000/insights` in your browser.

## Contributing

There are many ways you can contribute, even if you don't code:

1. Start by giving a star to this repository!
2. If you find any issues, even if it's a typo, you can [report a bug](https://github.com/empress-eco/insights/issues).
3. You can request a new feature [here](https://github.com/empress-eco/insights/issues).
4. Join our [telegram group](https://t.me/empress-eco) and share your thoughts.

## License and Acknowledgements

#### License
This project is under the MIT License. Your contributions are also licensed under the MIT License.

#### Acknowledgements
Special thanks to the Empress Community, the architects behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.