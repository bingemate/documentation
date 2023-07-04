# BingeMate Features

## MindMap

[XMind](https://xmind.works/share/vHmaBaXi)

[![BingeMate MindMap](BingeMate%20-%20Fonctionnalités.png)](https://xmind.works/share/vHmaBaXi)

## Users

### Auth

> Live reload of login sequence diagram
```bash
d2 --layout=dagre -t 101 login.d2 -w login.png
```
> Generate the login sequence diagram
```bash
d2 --layout=dagre -t 101 login.d2 login.png
```

![User Login](login.png)

## Api Gateway

### Oauth routes

> Live reload of oauth sequence diagram
```bash
d2 --layout=dagre -t 101 oauth_api_gateway.d2 -w oauth_api_gateway.png
```
> Generate the oauth sequence diagram
```bash
d2 --layout=dagre -t 101 oauth_api_gateway.d2 oauth_api_gateway.png
```

![Oauth Api Gateway](oauth_api_gateway.png)

## Media Indexer

### Transcode

> Live reload of transcode sequence diagram
```bash
d2 --layout=elk -t 101 media-indexer.d2 -w media-indexer.png
```
> Generate the transcode sequence diagram
```bash
d2 --layout=elk -t 101 media-indexer.d2 media-indexer.png
```

![Media Indexer](media-indexer.png)

## Streaming

### Stream

> Live reload of stream sequence diagram
```bash
d2 --layout=elk -t 101 streaming.d2 -w streaming.png
```
> Generate the stream sequence diagram
```bash
d2 --layout=dagre -t 101 streaming.d2 streaming.png
```

![Streaming](streaming.png)

### Streaming socket

![Streaming Socket](Diagramme_sans_nom.drawio_2.png)

## Payment

### Subscription

![Subscription](payment-service.drawio.png)