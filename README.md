web crawler using scrapy and redis

```zsh
# install python dependency
pip install scrapy redis

# run redis from docker
docker run --name web-crawler-redis -p 6379:6379 -d redis

# start crawling
scrapy runspider spider.py
```