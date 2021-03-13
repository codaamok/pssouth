# Create a new event post / listing

Create new event post using the below command:

```
hugo new --kind event events/2020-01-30
```

This will produce the following directory structure within the `content` directory:

```
content
│   ├───events
│   │   └───2020-01-30
│   │       │   index.md
│   │       └───images
│   │               .empty
```

Modify `index.md` with the event details and use the images directory if needed. You can reference images placed inside the `images` directory like so:

```
![](images/mypicture.jpeg)
```
