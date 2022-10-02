# Share Eazy

https://share-eazy.herokuapp.com

A file sharing web app, which allows the user to seamlessly share files on the internet

## Features

The user can upload any file upto 100 MB and share it either through: 
- The link which is generated automatically upon upload 
- By the entering the email of the receiver (We do not store emails or email ids of senders/receivers)
- Fully Responsive

## Tech Stack

**Client:** HTML, CSS, JavaScript

**Server:** Node, Express, MongoDB

## Demo

https://user-images.githubusercontent.com/51822103/189396854-84c57377-ad33-4f96-98f2-f437f4926798.mp4

## Screenshots

  Home Page
![Capture1](https://user-images.githubusercontent.com/51822103/189397107-77d9d16d-78b3-4061-b056-b4c8b023b30f.PNG)

  Download Page
![Capture5](https://user-images.githubusercontent.com/51822103/189397260-5d5b46ca-727f-4bab-878d-667687524c41.PNG)

  Page to share links to others and Send email
 ![Capture2](https://user-images.githubusercontent.com/51822103/189397549-93de8781-d34a-4bc0-8dbe-8e265ba69d15.PNG)

  Email Recieved 
 ![Capture3](https://user-images.githubusercontent.com/51822103/189397680-559d03d3-f9ba-4233-8af3-e958087a63db.PNG)

  Email Format
  ![Capture4](https://user-images.githubusercontent.com/51822103/189397781-15fd0f94-0735-4b62-bd1a-cb168b47d866.PNG)
  
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`PORT`

`SMTP_PORT`

`SMTP_HOST_URL`

`MONGO_URL`

`APP_BASE_URL`

`MAIL_USER`

`MAIL_PASSWORD`

`NODE_ENV`

## Run Locally

Clone the project

```bash
  git clone https://github.com/Salik47/ShareEazy.git
```

Go to the project directory

```bash
  cd ShareEazy
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run dev
```

## Authors

- [@Salik47](https://github.com/Salik47)
- [@NAEEMGHADAI](https://github.com/NAEEMGHADAI)

## Feedback

If you have any feedback, please reach out to us at mohdnaeemghadai@gmail.com


