# To start SocialPoll:
ENV variables:
export SP_TWITTER_KEY=yCKqlSPYdINYwHZ7rhJsZ34HP
export SP_TWITTER_SECRET=6olRwKHpzY6C1sIcBdmczdPi1PhSM8Ez4W102gJtV9YJWufT6K
export SP_TWITTER_ACCESSTOKEN=29481227-1q1bx9HU0Ra8lnSnNb1mjADp1pAXS2ST0Kf4xYhNE
export SP_TWITTER_ACCESSSECRET=Sp1ng22nZAw6uaYyFESDjlSBhFhYtGK8Idhe0OWjNX6Sr

```
nsqlookupd
```

```
nsqd --lookupd-tcp-address=localhost:4160
```

```
mongod --dbpath ./db
```

```
cd counter
go build -o counter
./counter
```

```
cd twittervotes
go build -o twittervotes
./twittervotes
```

```
cd api
go build -o api
./api
```

```
cd web
go build -o web
./web
```
