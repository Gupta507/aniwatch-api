# [3.0.0](https://github.com/ghoshRitesh12/aniwatch-api/compare/v1.34.0...v3.0.0) (2025-03-03)


### Bug Fixes

* added japanese anime names to all responses ([94664ab](https://github.com/ghoshRitesh12/aniwatch-api/commit/94664abdfdf1be8820f96afe081182f59281f4cb))
* **bundled_file_error:** update aniwatch pkg ([d65d0f1](https://github.com/ghoshRitesh12/aniwatch-api/commit/d65d0f17cc26f53b053ea74e0161e6fa006a6e0d))
* fixed tests regarding episode sources ([bf2c69e](https://github.com/ghoshRitesh12/aniwatch-api/commit/bf2c69e7abf161f611d8b5c85248d63548211e79))
* fixed using specific server for episode sources ([4437ef2](https://github.com/ghoshRitesh12/aniwatch-api/commit/4437ef24cc224e784701fbed2fa26e1ce90e04a5))
* **megacloud): `WebAssembly.instantiate(:** Argument 0 must be a buffer source` error ([374c87c](https://github.com/ghoshRitesh12/aniwatch-api/commit/374c87cf8a8fc47791a5da1215272cae6cee233a))
* **ts build error:** fixed ts build error due to conflicting types ([cb5a467](https://github.com/ghoshRitesh12/aniwatch-api/commit/cb5a4672a8c3b0729bbb4522a3af252f7b336b97))
* **vercel:** try1 to fix 'cannot find module puppeteer-extra-plugin-stealth' ([95d818e](https://github.com/ghoshRitesh12/aniwatch-api/commit/95d818e3713ced95e81323bc609459c6b106154a))
* **vercel:** try2 to fix 'cannot find module puppeteer-extra-plugin-stealth' ([f5ec625](https://github.com/ghoshRitesh12/aniwatch-api/commit/f5ec625c6ec2255ea61117ade842df424cd7aa85)), closes [/github.com/vercel/pkg/issues/910#issuecomment-1032839383](https://github.com//github.com/vercel/pkg/issues/910/issues/issuecomment-1032839383)
* **vercel:** try3 to fix 'cannot find module puppeteer-extra-plugin-stealth' ([3f81d6a](https://github.com/ghoshRitesh12/aniwatch-api/commit/3f81d6a3bb2d2744235fff19721c75f542e89a7f)), closes [/github.com/vercel/pkg/issues/910#issuecomment-1032839383](https://github.com//github.com/vercel/pkg/issues/910/issues/issuecomment-1032839383)
* **vercel:** try4 to fix 'cannot find module puppeteer-extra-plugin-stealth' ([4447819](https://github.com/ghoshRitesh12/aniwatch-api/commit/44478194e330f00070ab05ead36e13d87275d035)), closes [/github.com/vercel/pkg/issues/910#issuecomment-1374872029](https://github.com//github.com/vercel/pkg/issues/910/issues/issuecomment-1374872029)


* Aniwatch API Version 2 (#66) ([46f688a](https://github.com/ghoshRitesh12/aniwatch-api/commit/46f688ac12a99b8fb145b0745dd4cc6babff1e1e)), closes [#66](https://github.com/ghoshRitesh12/aniwatch-api/issues/66)


### Features

* **`/qtip`:** add new `/qtip` endpoint ([f0acd89](https://github.com/ghoshRitesh12/aniwatch-api/commit/f0acd89d87e5e62c12e20a95225ca9261fefe411))
* add `.editorconfig` ([90c0e86](https://github.com/ghoshRitesh12/aniwatch-api/commit/90c0e869abaae168bc07fe93782b65651f45dfc8))
* add `/v` endpoint for identifying api repo vesion ([062e662](https://github.com/ghoshRitesh12/aniwatch-api/commit/062e662fbcde1947694b39740b9896f75325959c))
* add `airingTimestamp` and `secondsUntilAiring` to `/anime/schedule` endpoint ([041c0b7](https://github.com/ghoshRitesh12/aniwatch-api/commit/041c0b7098ffb3d87a729d7dbfc774a96761d3c3))
* add `airingTimestamp` and `secondsUntilAiring` to `/anime/schedule` endpoint ([3f0b367](https://github.com/ghoshRitesh12/aniwatch-api/commit/3f0b367ae027370a81df716eb75c05703a1af905))
* add `jname` field to Anime interface ([c65d786](https://github.com/ghoshRitesh12/aniwatch-api/commit/c65d786673c4369b8d617a6972d01b7ad3a51954))
* add global constants ([54fe538](https://github.com/ghoshRitesh12/aniwatch-api/commit/54fe5389e13c3ae62a27c414af03cc6d5a260837))
* added `mostPopular`, `mostFavorite` and `latestCompleted` to the home route response ([5d92946](https://github.com/ghoshRitesh12/aniwatch-api/commit/5d929461ce918006b9c3977e5af5f76799e820b3))
* added episode count to top airing anime ([62fa83a](https://github.com/ghoshRitesh12/aniwatch-api/commit/62fa83a56d5e5ea4cc5e7b38b478208b0c5e6a72))
* added episode number to estimated anime schedule ([bdfebb5](https://github.com/ghoshRitesh12/aniwatch-api/commit/bdfebb5e320c15ae9de1a57a66b6a4602bcebf4d))
* **az-list:** add `/azlist/:sortOption` endpoint for scraping hianime's az-list animes ([861a897](https://github.com/ghoshRitesh12/aniwatch-api/commit/861a8979991dc2aaaa621e0e2bb9e016ad4dfe6c))
* **cache:** add `AniwatchAPICache` class to implement API caching layer ([b7d036d](https://github.com/ghoshRitesh12/aniwatch-api/commit/b7d036dbe29fcfa39c6573a0f02888093eb43d78))
* **cache:** add Cache-Control middleware and update .env.example ([f1f5db8](https://github.com/ghoshRitesh12/aniwatch-api/commit/f1f5db84f98818af2c047ea375832e5ded5f021a))
* **cache:** add cacheConfigSetter & cacheControlMiddleware by [#90](https://github.com/ghoshRitesh12/aniwatch-api/issues/90) ([5f1f216](https://github.com/ghoshRitesh12/aniwatch-api/commit/5f1f2167dfe2b99f53743e59c8354a6f8e886566))
* **cache:** add middleware to insert `CACHE_CONFIG` variable in request context ([da83048](https://github.com/ghoshRitesh12/aniwatch-api/commit/da83048f908c1505cc1157a8344ab1a75208130d))
* **cache:** integrated Redis caching layer for endpoint responses ([5cd99fc](https://github.com/ghoshRitesh12/aniwatch-api/commit/5cd99fcc642e54c1f26306a722d5ebeb8fff75a3))
* **envs:** standardized env examples and add new redis connection url env ([9d379ec](https://github.com/ghoshRitesh12/aniwatch-api/commit/9d379ec4fe99782dc8e5340f2895cf11399bb1f9))
* **errorHandling:** add error handlers config file ([da19fb7](https://github.com/ghoshRitesh12/aniwatch-api/commit/da19fb7e869c7a9f4007b8bf1439c08e5fe684f7))
* **future:** add hianime_v2 image ([1bba988](https://github.com/ghoshRitesh12/aniwatch-api/commit/1bba988e0d241121b51f9d9a9822da1237bd8aa8))
* **future:** add hianime_v2 social img ([332feca](https://github.com/ghoshRitesh12/aniwatch-api/commit/332feca25f9f287d5cdf82a5bb8cf8ebe2210d67))
* **megacloud:** integrate https://github.com/drblgn/rabbit_wasm 's solution ([2478279](https://github.com/ghoshRitesh12/aniwatch-api/commit/2478279db71633b2d84f86c67f3b8ce9e5cfe32e))
* **megacloud:** update aniwatch pkg ([cd41a54](https://github.com/ghoshRitesh12/aniwatch-api/commit/cd41a54a7ee968c2df8ad46de653c7617d13649f))
* **megacloud:** update aniwatch pkg, fixing `episode/sources` endpoint ([b70e654](https://github.com/ghoshRitesh12/aniwatch-api/commit/b70e65402eafec2e7d67f8335880bcb1dccccac5))
* **prettier:** add `.prettierignore` ([23fcd4a](https://github.com/ghoshRitesh12/aniwatch-api/commit/23fcd4a19f7da2817782d557b6d5e6f664b3b584))
* **prettier:** add `prettier.config.mjs` ([9ae824b](https://github.com/ghoshRitesh12/aniwatch-api/commit/9ae824b42c2665869e0a7bc964339ee6cc414d1a))
* **puppeteer:** add chromium deps and envs for seamless operation of puppeteer ([4275a65](https://github.com/ghoshRitesh12/aniwatch-api/commit/4275a65b9dc959e91a8eb388df5546b797c639a4))
* **server:** add aniwatch variables types for type-safe req context variable access ([db02218](https://github.com/ghoshRitesh12/aniwatch-api/commit/db022185efd04d4382883de543d3f3399cd28a6b))
* update allowed origins to include wildcard if env not present ([21a8718](https://github.com/ghoshRitesh12/aniwatch-api/commit/21a8718f87d7409d61970139e39c2bb0c6cfe91c))
* update dockerfile, remove chromium and related envs ([11462f3](https://github.com/ghoshRitesh12/aniwatch-api/commit/11462f309a6e73d041a8eafe12c0f6cdc3f5b9ac))
* use refactored error handlers and cache middlewares ([da6699b](https://github.com/ghoshRitesh12/aniwatch-api/commit/da6699ba224451e0d1a1d2cac569d314ea9c29b3))


### BREAKING CHANGES

* * chore: remove files that are not necessary for api v2

* test: update existing tests to use  pkg

* feat: organized aniwatch api envs and add more info about them

* feat: update tsconfig to include strict noUnsed params

* feat(api homepage): revamp api home page

* feat: update wani kuni image

* feat: add dot img

* feat: use hono cors

* feat: use hono rate limiter

* build: remove unnecessary deps, add ones needed and update description

* feat: add hianime routes and their handlers

* feat: update vercel deployment file

* docs: update logo and scraper docs, add envs section

* feat: update main server file

* feat: update peronal deployments caution section



# [1.34.0](https://github.com/ghoshRitesh12/aniwatch-api/compare/v1.33.4...v1.34.0) (2024-06-11)


### Features

* update rate limit to 6 reqs every 30 mins ([8d82f44](https://github.com/ghoshRitesh12/aniwatch-api/commit/8d82f448963dcf54c75dc93ea572f104dffcc9fb))



## [1.33.4](https://github.com/ghoshRitesh12/aniwatch-api/compare/v1.33.3...v1.33.4) (2024-06-11)



## [1.33.3](https://github.com/ghoshRitesh12/aniwatch-api/compare/v1.33.2...v1.33.3) (2024-05-10)



## [1.33.2](https://github.com/ghoshRitesh12/aniwatch-api/compare/v1.33.1...v1.33.2) (2024-05-10)



