Project makes a loopback of a message using MQTT broker to save the data into DB.

It downloads spring-boot project from https://github.com/viamandi/msg_loopback

It contains docker yml to launch images for:
- download spring project and compiling it
- MQTT broker: HiveMQ
- Spring App application
- PostgreSQL to save the data from the message


Run:
  - Precondition:
    - install docker
  - docker-compose -up
