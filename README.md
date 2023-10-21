# InsecureJWT-Lab
An application wantedly vulnerable to various JWT related attacks. Hack it &amp; patch it!


## Deployment

To deploy this follow the below steps - 

    1. Set Up a Web Server:
    You need a local PHP web server to host the project.

    2. Configure PHP:
    Make sure PHP is installed and configured on your server.

    3. Clone Your GitHub Repository: 
        git clone https://github.com/rishaldwivedi/InsecureJWT-Lab.git
 


## Usage guide

#### Credential



| User | Password     | Description                |
| :-------- | :------- | :------------------------- |
| `user` | `pass` | You don't need multiple accounts |

#### Configuration

```http
  /config/config.php
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `define('WEBROOT_PATH', '/var/www/htdocs/');`      | `WEBROOT` |  |
| `define('VULNERABILITY', 'jku_hijack');`      | `Vulnerability` |  jku_hijack, key_confusion, none_algorithm, weak_secret, kid_injection|



## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## Authors

- [@rishaldwivedi](https://www.github.com/octokatherine)

