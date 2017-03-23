---
title: Realms API
---
## Realms API
Mojang have a private API for interacting with their Realms servers. Here i will try to work out what all the fields mean so people can make their own API clients.

### Base info
|              |      |
| : -----  |      |
| Host | pocket.realms.minecraft.net:443 |
| Authorization | **TODO** |
| User agent | MCPE/Android |
| Client version | *(MCPE Version, e.g. 1.0.4)* |
| Cache control | No cache |
| Charset | UTF-8 |


### Endpoints
In the future i will add individual pages for each endpoint.

| Path            |     Description      |
| : ----------- | : --------------- |
|  /worlds       |     **TODO**        | 
| /activities/live/players | **TODO** |
| /mco/client/compatible | **TODO** |

 
##### And here is one of the GET requests that i captured, just for reference
```
GET /worlds HTTP/1.1
Host: pocket.realms.minecraft.net:443
Authorization:XBL3.0 x=179553430866589705;eyJlbmMiOiJBMTI4Q0JDK0hTMjU2IiwiYWxnIjoiUlNBLU9BRVAiLCJjdHkiOiJKV1QiLCJ6aXAiOiJERUYiLCJ4NXQiOiJfd3lzeEV6dHY4UmdGLWl4cjltdy1LTTNaUG8ifQ.0Ab-pEz6JdK5SaqaVRsAjGYwcB9rij5oH4hBTVMGOCCpYrf8NxZzp5eH2Sd4RyTL6PW2gvb5vlqklfcIgZnsv7Aq4feIgSgdExPYluUa5E1ifJgVijX2iO3HN14pVHug2n23bwqj4eE80y-VILWEYCvzf08d7Jj69T7KiaKKI9_VbBCJ4BhhbEtDmDwfi10UZKewVQDbTnqF98vakA69dwkjWcdoIhUNDAfBzF3IkAEAM6BLQVuOxF07_63aaMPGJmEabf0GJCLMDvuvq1FsNOs1Bp_D9pnz8UPivneRegkOYiNcMMrlO49hjwF0L-VQ1e4PKjK5z82zy_qSJBSSdA.1SS8wj9xocMLPRicVC0WkA.qIrIQ38oKQaS2C82J_KabO_lfi3r56ulQ-SzfE2qFQaYrpFuIFeZy9A2wUW4ScXDivDLCzSRLgSEeGkFkSnwr8b0J692BGXbj3KAjjsjcAqYo6yJVJ3t9PGJjzM3iCmsfmSY_WnoHpszoTCsM_7euDucw1ITkZatlalwXVh8hbAZyUzfxFkqVU6ukTyJn21D8E49BblUi-SPV5socBX1tFNGAkLN0iz9DcDoq_3suTTQB11V2NNEv0NG_nS3Po4_WYg0x-gGXifYyTSULU39-XuuQfcSm_2dt4R4lHMKoGp8gjKK3uiVadvCrRCd4M2jqsjDNPP2s6jTzk-c3GR783W94BeEjpLBodeiuH18R4b4SdjiNGcT_3hhrCzwN0VtEsQpku_oUEHjwMCp00J1_fhBzn0UHHG3ONXRA88BYOG8TRhF_qeWa2qUVcMrDzoP_hRfAbL-qaYHRLdL9SNrhFQ4yrS88aQ4E8f23-G-lhwca0R7VXJd9sZZKLwG4YbA10wqWufh2scn4m5y5khBFNNz-n3Pa2aF6GBfkR-t-FWYvO-pQEmjRwLFthT-d-ZkzCfaSJ6xSIdeAnuqZ_zvr2D8OcyXQpco8DEBtiPOeF200oGP7uMUUB9AKomi_2IrSwAB9Gj3PhxsKUeA8zjxsyDVW57_yDkyU_DRcKvuwF9rtGJLg2hxQ32E4qh-wifssYAsZ3AURuH8AAMk1UtACvfhq1hNiEnYkM6R8bu7qHSvw26h10UsDEn039cV5PnYHorTsqH3WAG8Tkmhz-jc7LJi6TV99OGqXYZ_EZzEQ-NUxBzVgwTaT4SPaFtoc8jy-Bw3q2rTKEoeTZErkg3cZkjxxDKLFjM8fERXJ23A6PdFEkM2aBND_nH5I65CXpNo22DorKunDA25jS7vs8SwGElvW89_mdVfBxMzDJNRWVrM1WYXZBAZGRabzc5CTy8LBg2Sfi4BEP2FLqVFjvjF3JQ176gKpj1OoX7dW1sGkdTF2vtAP6qqWL2NO8OOuWIGWK8-MIpRG0_BxxeBFbISOTfaY7q6A2WBPI0UH0qtmYSp24PW6qcfK_09FZiojjGoowl6KfJotQffEROHofASSUAC4pEtDwKF307u6f0_GZ6s7EcXmzjxPfjKzBW3oTZvHTbXlN6jclth-8iSZyEDZUgaPUuxZlfjVwoWzS8rrlDPfKKcOj8PNZog990iAIQGYZrBMVDfxslT8-mhznwX0w.NjS1cFPgItKqoOZ8MIl_SwN_aOCWenGemyPeVRcIP7U
Cache-Control:no-cache
Charset:utf-8
Client-Version:1.0.4
User-Agent:MCPE/Android
Connection: Keep-Alive
```
