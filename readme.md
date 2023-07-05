# Readme.md

## For client side

- there is nothing much to do for frontend part, just launch the client side on localhost or with github page.
- For github page, Make sure your files are in the root directory.Otherwise it will give 404 error.

## Configuration : First Things First (For Server side)

1. `npm init -y` initialize it first
2. install the  required dependencies `npm install express nodemailer body-parser dotenv`
3. Define following environment variable
   - `EXPRESS_EMAIL_ID`
   - `EXPRESS_PASSWORD`
   - `EXPRESS_SMTP_SERVER`
   - `EXPRESS_SMTP_PORT`
   - `EXPRESS_RECEIVER_EMAIL_ID`
   - `EXPRESS_PORT`

## To Execute or Start the server

- start the server: `npm start`

## Troubleshoot

- make sure project/directory name is in lowercase. otherwise at time to `npm init -y` it will throw an error.
  - if doesn't want to change the name initialize manually using `npm init` command.
