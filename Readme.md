# JSSER
1.Copy the code below

```js
javascript:(function(){var scripts=document.getElementsByTagName("script"),regex=/(?<=(\"|\'|\`))\/[a-zA-Z0-9_?&=\/\-\#\.]*(?=(\"|\'|\`))/g;const%20results=new%20Set;for(var%20i=0;i<scripts.length;i++){var%20t=scripts[i].src;""!=t&&fetch(t).then(function(t){return%20t.text()}).then(function(t){var%20e=t.matchAll(regex);for(let%20r%20of%20e)results.add(r[0])}).catch(function(t){console.log("An%20error%20occurred:%20",t)})}var%20pageContent=document.documentElement.outerHTML,matches=pageContent.matchAll(regex);for(const%20match%20of%20matches)results.add(match[0]);function%20writeResults(){results.forEach(function(t){document.write(t+"<br>")})}setTimeout(writeResults,3e3);})();
```
2. Go to Bookmarks Manager


   <img width="642" alt="Screenshot 2024-05-27 at 02 14 39" src="https://github.com/whalebone7/Jsser/assets/125891350/40188e08-384e-44a7-bdc8-2940b7419c11">

3. Paste

<img width="515" alt="Screenshot 2024-05-27 at 02 16 55" src="https://github.com/whalebone7/Jsser/assets/125891350/e7111414-1313-4f53-8ccd-21e42c74fa7b">

4. Click `jsser`for output

   
<img width="1280" alt="Screenshot 2024-05-27 at 02 18 17" src="https://github.com/whalebone7/Jsser/assets/125891350/d9e0951d-d8f8-4085-8236-ac8804ea30c6">


<img width="1280" alt="Screenshot 2024-05-27 at 02 18 45" src="https://github.com/whalebone7/Jsser/assets/125891350/a059434a-2519-446d-93be-65eda11cba18">


