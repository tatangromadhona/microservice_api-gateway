# Online Course - Api Gateway

[![ONLINECOURSE Logo](https://ik.imagekit.io/tatangdev/online-course/Asset_5__ELvljTjxona.png)](https://github.com/tatangromadhona/online-course_api-gateway)

## Online Course

ONLINECOURSE is an udemy-like online course platform built using microservices architecture.
| Structure |
| --- |
| [![ONLINECOURSE Logo](https://ik.imagekit.io/tatangdev/online-course/Asset_5_rXsSNbDR84.png)](https://github.com/tatangromadhona/online-course_api-gateway) |

## Api Gateway

Implement an API gateway that is the single entry point for all clients. The API gateway handles requests in one of two ways. Some requests are simply proxied/routed to the appropriate service. It handles other requests by fanning out to multiple services.

Rather than provide a one-size-fits-all style API, the API gateway can expose a different API for each client. For example, the Netflix API gateway runs client-specific adapter code that provides each client with an API that’s best suited to its requirements.

The API gateway might also implement security, e.g. verify that the client is authorized to perform the request

This Api-Gateway is built using ExpressJS Framework.

## Another Services

| User Service | Media Service | Course Service | Payment Service |
| --- | --- | --- | --- |
| [![User Service](https://ik.imagekit.io/tatangdev/online-course/Asset_3_cn6ASO3xsi7.png)](https://github.com/tatangromadhona/online-course_user-service) | [![Media Service](https://ik.imagekit.io/tatangdev/online-course/Asset_4_YykdDSbga.png)](https://github.com/tatangromadhona/online-course_media-service)| [![Course Service](https://ik.imagekit.io/tatangdev/online-course/Asset_2_7ZFU6kkrO.png)](https://github.com/tatangromadhona/online-course_course-service)| [![Payment Service](https://ik.imagekit.io/tatangdev/online-course/Asset_1_M1tYLXCSBX.png)](https://github.com/tatangromadhona/online-course_payment-service)
