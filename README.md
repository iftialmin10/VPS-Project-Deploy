# VPS Project Deployment

## Step-1

First enter VPS IP address

```js
sss root@<ip address>
```

Then enter your password

```js
root@<ip address>'s password:
```

## Step-2

Go to www folder

```js
cd /var/www
```

Check all project

```js
ls;
```

## Step-3

Clone your github project

```js
git clone githubsshkey
```

## Step-4

```js
ls;
```

```js
cd git_repo_folder
```

```js
npm i
```

```js
npm run build
```

```js
npm run dev
```

## Step-5 enable port

```js
sudo ufw enable
```

```js
sudo ufw status
```

```js
sudo ufw allow 5008
```

```js
sudo ufw status
```

```js
npm run start
```

```js
sudo ufw reload
```

## Step-6 for live server

```js
npm i -g pm2
```

```js
pm2 start npm --name "vps-project-deploy" -- start
```

```js
pm2 logs vps-project-deploy
```

```js
pm2 ls
```
