# ☗ Counter

> 多种风格可选的萌萌计数器

<img src="https://counter.due.moe/get/@counter.github?theme=urushi" width="50%">

## Usage

### Local

```shell
$ git clone https://github.com/Fuwn/counter.git
$ cd counter
$ npm install # Or Bun, Yarn, pNPM, etc.
$ npm run start
```

### Docker

```yaml
docker run --volume 'counter:/app/data' -p '80:3000' --rm fuwn/urushi-counter:latest
```

### Database

`counter` will use SQLite by default, and will place the database file, `count.db`, within the `data/` directory of the root project folder.

#### MongoDB

To use MongoDB instead of SQLite, expose a `DB_URL` environment variable.

```shell
export DB_URL=mongodb+srv://user:password@mongodb.example.com/counter
```

### Resource Attributions

*   [A-SOUL_Official](https://space.bilibili.com/703007996)
*   [Moebooru](https://github.com/moebooru/moebooru)
*   [Rule 34](https://rule34.xxx) (NSFW)
*   [Gelbooru](https://gelbooru.com) (NSFW)

### License

This project is licensed with the [MIT License](LICENSE).

