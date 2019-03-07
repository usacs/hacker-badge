# API Reference

## Introduction
**GET** — `/api/v1/`

The api is mounted on the `/v1/` subroute of `/api/`. This is version **1**. Mouting the API onto `v1` versus mounting it directly onto `/api/` makes transitioning between different versions much easier.

## Authentication
**POST** — `/api/v1/auth/login`
This is the login method. It takes in a json body containing `email` and `password` properties. When sucessfull, it should return a json containing a `token` and a `success` property.

**POST** - `/api/v1/auth/signup`
Login method. Takes in a email, username, and password. Returns success and token

**POST** `/api/v1/auth/verifyEmail`
Login method. Takes in a email, username, and password. Returns success and token

`POST` `/api/v1/auth/verifyUsername`
Login method. Takes in a email, username, and password. Returns success and token

`POST` `/api/v1/auth/deleteUser/`
Login method. Takes in a username and password. Returns success and token

## User

`POST` `/api/v1/auth/login`
Login method. Takes in a email (or username) and password. Returns success and token

`POST` `/api/v1/auth/signup`
Login method. Takes in a email, username, and password. Returns success and token

`POST` `/api/v1/auth/verifyEmail`
Login method. Takes in a email, username, and password. Returns success and token

`POST` `/api/v1/auth/verifyUsername`
Login method. Takes in a email, username, and password. Returns success and token

`POST` `/api/v1/auth/deleteUser/`
Login method. Takes in a username and password. Returns success and token

## Services

`GET` `/api/v1/services/body/:service/:projectName`
Login method. Takes in a username and password. Returns success and token
Servies. Github .Devpost.
returns a list of projects as a json array, has body, project name, etc

`GET` `/api/v1/services/previews/:service`
Login method. Takes in a username and password. Returns success and token
Servies. Github .Devpost.
returns a list of projects as a json array, has body, project name, etc
