# Medium Posts Card For Github Profile :card_index:

Fetch your medium blog posts and display it as cards in your GitHub ReadMe.

```
[![Sabesan96](https://github-readme-medium-card.vercel.app/getMediumBlogs?username=sabesan96&type=horizontal)](https://medium.com/@sabesan96)
```

[![Sabesan96](https://github-readme-medium-card.vercel.app/getMediumBlogs?username=sabesan96&type=horizontal&limit=3)](https://medium.com/@sabesan96)

### How to use

- Go to your repository

- Add the following section to your **README.md** file. replace `USERNAME` with your real medium username (without @ sign)

```
[![USERNAME](https://github-readme-medium-card.vercel.app/getMediumBlogs?username=USERNAME)](https://medium.com/@USERNAME)
```

### Options

You can customize the appearance of your `medium cards` for your use case, following are the list of options available:

| Option       | Default Value | Description                                                                             | Required |
| ------------ | ------------- | --------------------------------------------------------------------------------------- | -------- |
| `?username=` | `""`          | Your Medium username                                                                    | Yes      |
| `&limit=`    | `5`           | Maximum number of medium post cards you want to show on your readme, all feeds combined | No       |
| `&type=`     | `vertical`    | your medium blog post cards alignment could be `horizontal` or `vertical`               | NO       |

### Deploy your own

Deploy this code to your vercel account.[![Vercel Deploy](https://vercel.com/button)](https://vercel.com/import/git?s=https://github.com/sabesansathananthan/github-readme-medium-card)

### License

[MIT License](./LICENSE)
Copyright (c) 2020 [Sathananthan Sabesan](https://github.com/sabesansathananthan)
