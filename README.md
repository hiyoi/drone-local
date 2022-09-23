## drone local

### install and start

- follow the [guide](https://docs.drone.io/server/provider/github/) and fill the mask in *.env file

- `docker-compose up -d`



### generate shared key

`openssl rand -hex 16`


### use ngrok forward traffic

- setup [ngrok](https://dashboard.ngrok.com/get-started/setup)
- start ngrok `ngrok http 8088`
- [github oauth](https://github.com/settings/developers) setting
<img width="855" alt="image" src="https://user-images.githubusercontent.com/2487038/191911341-5b28d15d-cb27-47be-935a-6a579630ac55.png">


### screenshot
![image](https://user-images.githubusercontent.com/2487038/191910659-eff8c210-2ebe-4bca-abff-d704a659a059.png)
