# OJK Invest API

- Submitted At: 2021-01-13
- Updated At: 2021-02-02
- Status: In Progress
- Repository: _private for now_

## Summary

Create a public API that provides information about legal and ilegal investments in Indonesia. The data is scrapped from OJK's investment data.
## Motivation

The recent popularity of VTube (not to be confused with _virtual youtuber_) application 

## Stack

A simple NodeJS application will do. Scrapping will be done with ~~simple HTTP agent~~ [Puppeteer](https://pptr.dev/). The API will be deployed on [Vercel Now](https://vercel.com). The data will be refreshed everyday with [GitHub Actions](https://github.com/features/actions).

## Current Progress

- [x] Find all URLs of interest to be scrapped from
- [x] Learn how to web works, especially how the request and response is handled.
- [x] ~~Decode all required parameters~~
- [x] Create the scrapping script
- [x] Create the API
- [x] Create the documentation 
- [ ] Test GitHub Action
- [ ] Public release!

