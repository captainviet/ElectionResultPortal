# DEPLOYMENT GUIDE

1. Login to VNNTU admin dashboard
2. Reconfigure
  ```
  const config = {
    interval: 10000, // rate of opening vote, in ms
    url: 'http://host/endpoint', // URL of the API endpoint
    chase: '20180331T2000', // The Chase opening time, in yyyymmddThhmm format
    minVote: n, // minimum number of votes
    perPixel: m, // width of each vote for candidates (recommended 20)
    preChaseMsg: '...', // message to be displayed along timer before The Chase, can leave as it is
  }
  ```
3. [Minifyjs](https://jscompress.com) and replace script in `index.html`
4. Go to the chase page **Edit Page**
5. Paste content of `index.html` to the **Text editor**
6. Paste content of `index.css` to the **Page Specific Stylesheet** at the
   bottom of the page
