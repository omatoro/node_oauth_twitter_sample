node_oauth_twitter_sample
=========================

## 必要なnode modules
1. express
2. ejs
3. passport
4. passport-twitter


## 必要なファイル

`./server/oauth/test.js`に以下のように必要なデータを記述する。

```javascript
/**
 * twitter oauth test
 */
(function(ns) {
  ns.consumerKey    = "--insert--consumerKey";
	ns.consumerSecret = "--insert--consumerSecret";
})(exports);

```
