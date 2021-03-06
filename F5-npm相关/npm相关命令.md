# <span id='top' style='font-size:22px;color:#ff8000;'>ð npmå½ä»¤ç¸å³ ð</span><sub style='font-size:15px;'>[ï¼ðè¿åREADMEðï¼](/README.md)</sub>
> <span style='color:red'>æ³¨é1ï¼ç¹å»ä¸è¡¨ä¸­çå½ä»¤åç§°ï¼å¯ç´æ¥è·³è½¬å°å¯¹åºå½ä»¤æå¨ä½ç½®</span>
> <p style='color:red'>æ³¨é2ï¼ææå½ä»¤æåä¸ååå</p>

## <span style='font-size:18px;color:#ff8080;'>ð å½ä»¤é¾æ¥è¡¨</span>

| <span id='list'>å½ä»¤é¾æ¥è¡¨</span>|
|:-:|
|[æ¥çéåéç½®å°å](#1)|
|[è®¾ç½®æ·å®éå](#2)|
|[è®¾ç½®npméå](#3)|
|[æ¥çnpmçæ¬](#4)|
|[åå§åæä»¶](#5)|
|[å®è£ä¾èµ](#6)|
|[å¸è½½æå®ä¾èµå](#7)|
|[æ¥çå·²å®è£çå](#8)|
|[npm å¸®å©å½ä»¤](#9)|
|[æ´æ°æå®å](#10)|
|[æ¥çéç½®ä¿¡æ¯](#11)|
|[æ¥çå®è£åè·¯å¾](#12)|
|[æ¥çæ¯å¦å®è£å¯¹åºåä»¥åçæ¬ä¿¡æ¯](#13)|
||

## <span style='font-size:18px;color:#ff8080;'>ð å·ä½å½ä»¤ä»¥åç¸å³è§£é</span>

### ð <span id='1'>æ¥çéåéç½®å°å</span><span style='font-size:10px;'>------[è¿ååè¡¨](#list)</span>

```
npm get registry
```

### ð <span id='2'>è®¾ç½®æ·å®éå<span><span style='font-size:10px;'>------[è¿ååè¡¨](#list)</span>

```
npm config set registry https://registry.npm.taobao.org
```

### ð <span id='3'>è®¾ç½®`npm`éå<span><span style='font-size:10px;'>------[è¿ååè¡¨](#list)</span>

```
npm config set registry https://registry.npmjs.org
```

### ð <span id='4'>æ¥ç`npm`çæ¬<span><span style='font-size:10px;'>------[è¿ååè¡¨](#list)</span>

```
npm -v
```

### ð <span id='5'>åå§åæä»¶<span><span style='font-size:10px;'>------[è¿ååè¡¨](#list)</span>

```
npm init
<!-- å¢å -yå¯ä»¥å¿«éçæé»è®¤çpackage.jsonæä»¶ -->
npm init -y
```

> ä½¿ç¨`npm init` å½ä»¤åï¼ä¼å¨å½åæä»¶å¤¹ä¸­çæä¸ä¸ª`pakeage.json`æä»¶ï¼æ­¤æä»¶ç¨æ¥è®°å½å½åé¡¹ç®çè¯¦ç»ä¿¡æ¯ä»¥åæä»¬å®è£åçç¸å³ä¿¡æ¯ã

### ð <span id='6'>å®è£ä¾èµ<span><span style='font-size:10px;'>------[è¿ååè¡¨](#list)</span>

> 1.å¨é¨å®è£ï¼ä¼æ ¹æ®é¡¹ç®ä¸­ç`package.json`æä»¶ä¸­çä¿¡æ¯ï¼ä¸è½½ææé¡¹ç®æä¾èµçåã

```
npm install 
æè 
npm i
```

> 2.å·ä½å®è£ï¼å®è£æå®çä¾èµåï¼æå®ä¾èµåççæ¬ã

```
// ä¸è¬å®è£
npm install xxx
// åªç¨äºå¼åç¯å¢
npm install xxx --save-dev
<!-- ä¼åå¸äºçäº§ç¯å¢ -->
npm install xxx --save
<!-- æå®åºå®çæ¬çä¾èµå -->
npm install xxx@1.0.1
```

### ð <span id='7'>å¸è½½æå®ä¾èµå<span><span style='font-size:10px;'>------[è¿ååè¡¨](#list)</span>

```
npm uninstall  xxx
```

### ð <span id='8'>æ¥çå·²å®è£çå<span><span style='font-size:10px;'>------[è¿ååè¡¨](#list)</span>

```
<!-- å½å -->
npm list
<!-- å¨å± -->
npm list -g 
```

### ð <span id='9'>`npm` å¸®å©å½ä»¤<span><span style='font-size:10px;'>------[è¿ååè¡¨](#list)</span>

```
npm --help
```

### ð <span id='10'>æ´æ°æå®å<span><span style='font-size:10px;'>------[è¿ååè¡¨](#list)</span>

```
npm update xxx 
```

### ð <span id='11'>æ¥çéç½®ä¿¡æ¯<span><span style='font-size:10px;'>------[è¿ååè¡¨](#list)</span>

```
npm config list
```

### ð <span id='12'>æ¥çå®è£åè·¯å¾<span><span style='font-size:10px;'>------[è¿ååè¡¨](#list)</span>

```
<!-- å½å -->
npm root
<!-- å¨å± -->
npm root -g
```

### ð <span id='13'>æ¥çæ¯å¦å®è£å¯¹åºåä»¥åçæ¬ä¿¡æ¯<span><span style='font-size:10px;'>------[è¿ååè¡¨](#list)</span>

```
npm ls xxx 
<!-- å¨å±æ¥è¯¢ -->
npm ls xxx -g 
```
-----
[ð è¿åè¡¨](#back)<br/>
[ð è¿åé¡¶é¨](#top)<br/>
[ð è¿åREADME](/README.md)

## <span style='font-size:18px;color:#ff8080;'>â­ï¸ åèé¾æ¥</span>

- ð© NPMä¸­æç½ : <https://www.npmjs.cn/>