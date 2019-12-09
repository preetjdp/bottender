# LINE rich menu submenu

## Install and Run

Download this example or clone [bottender](https://github.com/Yoctol/bottender).

```sh
curl https://codeload.github.com/Yoctol/bottender/tar.gz/master | tar -xz --strip=2 bottender-master/examples/line-rich-menu-submenu
cd line-rich-menu-submenu
```

Install dependencies:

```sh
npm install
```

You must put `accessToken` and `channelSecret` into `index.js`.

After that, you should follow this [document](https://bottender.js.org/docs/channel-line-rich-menu) to set up the rich menu on LINE. You can use the file `rich_menu.jpg` as the rich menu image.

Next, you can run the bot with this npm script:

```sh
npm run dev
```

This command will start server for bot developing at `http://localhost:5000`.

If you successfully start the server, you will get a webhook url like `https://xxxxxxxx.ngrok.io/webhooks/line` from command line.

## Set webhook

To set the webhook, go to [LINE developers console](https://developers.line.me/console/) and use the webhook url you get from running `npm run dev` to edit webhook information for your channel.

## Idea of this example

This example is a simple bot running on [LINE](https://line.me/) to demonstrate how to use rich menu.
For more information, check our [LINE API Document](https://developers.line.biz/en/reference/messaging-api/#rich-menu).

## Related examples

- [line-hello-world](../line-hello-world)
- [line-rich-menu](../line-rich-menu)