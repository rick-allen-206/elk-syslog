# ELK-Syslog

ELK-Syslog is an out of the box ready to deploy containerized syslog server that runs on ELK. Ready to 
deploy in a singe docker-compose up statement. 

Currently Logstash is setup to explicityly interperate Cisco logs, all other logs are handled generically. If 
you'd like to see additional logs supported by this deployment feel free to reach out with an example of the 
log you want parsed. 

## Installation

** Ensure that docker and docker-compose are installed first **

Clone this repository

```
cd elk-syslog
docker-compose up
```

## Usage

```
Direct syslogs to UDP or TCP port 5140
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
