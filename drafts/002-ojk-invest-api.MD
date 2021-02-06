# OJK Invest API

- Submitted At: 2021-01-13
- Updated At: 2021-02-04
- Status: Finished
- Repository: [Link](https://github.com/Namchee/ojk-invest-api)

## Summary

Create a public API that provides information about legal and ilegal investments in Indonesia. The data is scrapped from OJK's investment data.
## Motivation

The recent popularity of VTube (not to be confused with _virtual youtuber_) application has made people who previously ignorant didn't care much about investments became curious and learn more about the world of investments.

According to OJK, [VTube is an ilegal investment application](https://kumparan.com/kumparanbisnis/satgas-waspada-investasi-ojk-tegaskan-vtube-belum-punya-izin-masih-ilegal-1v4qptXlSeP). That kind of news made people wonder about the legality of investment products that have been circulating so far.

The fastest way to search for that particular information is by directly going through [OJK's website](https://www.ojk.go.id/Default.aspx) and search the data yourself. However, this is unpractical in some sense, since the website itself has too many pages on it. Plus, the website itself is pretty unreliable, sometimes it's unaccessable or it's really slow. To add a cherry to the cake, the data itself is somewhat confusing and badly formatted. These are the shortcomings that drive the need of an easy and well-formatted public API to access those data.

## Stack

A simple NodeJS application will do. Scrapping will be done with ~~simple HTTP agent~~ [Puppeteer](https://pptr.dev/). The API will be deployed on [Vercel Now](https://vercel.com). The data will be refreshed everyday with [GitHub Actions](https://github.com/features/actions).

## Current Progress

- [x] Find all URLs of interest to be scrapped from
- [x] Learn how to web works, especially how the request and response is handled.
- [x] ~~Decode all required parameters~~
- [x] Create the scrapping script
- [x] Create the API
- [x] Create the documentation 
- [x] Test GitHub Action
- [x] Public release!
