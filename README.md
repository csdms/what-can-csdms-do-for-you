# what-can-csdms-do-for-you

A presentation on CSDMS products, services, and events.

## presentation

Present these slides with [reveal-md](https://github.com/webpro/reveal-md) through their public Docker image:
```
git clone https://github.com/csdms/what-can-csdms-do-for-you
docker run --rm -p 1948:1948 -p 35729:35729 -v $PWD/what-can-csdms-do-for-you:/slides webpronl/reveal-md:latest /slides --watch
```
The service is now running at http://localhost:1948.

Or, install and run reveal-md locally (with `-w` to autoupdate on change):
```
reveal-md csdms.md -w
```
