# data-youtube-video-id

sample data set of YouTube video IDs, from cron jobs facing the YouTube Data API

### Quick Check

At this time, there appear to be 64 unique chararacters available for the YouTUbe video IDs.

List all video IDs in a string:
```javascript
const str = `
...
...
...
`;
```

Process the video IDs:
```javascript
[... new Set(str.trim().split('\n').join('').split('').sort())].join('')
```

View all 64 characters:
```
-0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZ_abcdefghijklmnopqrstuvwxyz
```
