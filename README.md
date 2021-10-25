<img src="https://img.shields.io/github/issues/WikiMovimentoBrasil/ijc?style=for-the-badge"/> <img src="https://img.shields.io/github/license/WikiMovimentoBrasil/ijc?style=for-the-badge"/> <img src="https://img.shields.io/github/languages/top/WikiMovimentoBrasil/ijc?style=for-the-badge"/>
# Introdução ao Jornalismo Científico

This app presents a collection of tools for managing activities and documents related to the course [Introdução ao Jornalismo Científico at pt wikiversity](https://pt.wikiversity.org/wiki/Introdu%C3%A7%C3%A3o_ao_Jornalismo_Cient%C3%ADfico). 

It allows users to view the course's program and sign up for it. Once registered, the user is able to view the different modules required to complete the program. The user can require a certificate to be issued once the course is completed. There is also an option to validate documents based on it's ID.

This tool is available live at: https://ijc.toolforge.org/

## Installation

There are several packages need to this application to function. All of them are listed in the <code>requeriments.txt</code> file. To install them, use

```bash
pip install -r requirements.txt
```

You also need to set the configuration file. To do this, you need [a Oauth consumer token and Oauth consumer secret](https://meta.wikimedia.org/wiki/Special:OAuthConsumerRegistration/propose).
Your config file should look like this:
```bash
SECRET_KEY: "<SECRET_KEY>"
BABEL_DEFAULT_LOCALE: "pt"
APPLICATION_ROOT: "ijc/"
OAUTH_MWURI: "https://meta.wikimedia.org/w/index.php"
LANGUAGES: ["pt","en"]
CONSUMER_KEY: "<CONSUMER_KEY>"
CONSUMER_SECRET: "<CONSUMER_SECRET>"
COORDINATORS_USERNAMES: ["COORDINATOR_1","COORDINATOR_2"]
NUMBER_OF_MODULES: <NUMBER_OF_MODULES>
ENCRYPTION_KEY: "<ENCRYPTION_KEY>"
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[GNU General Public License v3.0](https://github.com/WikiMovimentoBrasil/wikimarcas/blob/master/LICENSE)

## Credits
This application was developed by the Wiki Movimento Brasil User Group and the Museu do Ipiranga, supported by the University of São Paulo and the University of São Paulo Support Foundation.