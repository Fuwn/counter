# ☗ Counter

> 多种风格可选的萌萌计数器

<img src="https://counter.due.moe/get/@counter.github?theme=urushi" width="50%">

## Installation

### Self-hosting

```shell
$ git clone https://github.com/Fuwn/counter.git
$ cd counter
$ yarn install
$ yarn start
```

### Configuration

```yaml
# config.yml

app:
  # site: https://counter.due.moe
  port: 3000

db:
  type: sqlite # sqlite, mongodb
```

#### MongoDB

Expose a `DB_URL` environment variable

```shell
export DB_URL=mongodb+srv://user:passwd@***.***.***.mongodb.net/db_count
```

### Resource Attributions

*   [A-SOUL_Official](https://space.bilibili.com/703007996)
*   [Moebooru](https://github.com/moebooru/moebooru)
*   [Rule 34](https://rule34.xxx) (NSFW)
*   [Gelbooru](https://gelbooru.com) (NSFW)

### License

This project is licensed with the [MIT License](LICENSE).

