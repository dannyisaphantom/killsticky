# killsticky

```
javascript:(function()%7Bdocument.querySelectorAll(%22body%20*%22).forEach(function(node)%7Bif(%5B%22fixed%22%2C%22sticky%22%5D.includes(getComputedStyle(node).position))%7Bnode.parentNode.removeChild(node)%7D%7D)%3Bdocument.querySelectorAll(%22html%20*%22).forEach(function(node)%7Bvar%20s%3DgetComputedStyle(node)%3Bif(%22hidden%22%3D%3D%3Ds%5B%22overflow%22%5D)%7Bnode.style%5B%22overflow%22%5D%3D%22visible%22%7Dif(%22hidden%22%3D%3D%3Ds%5B%22overflow-x%22%5D)%7Bnode.style%5B%22overflow-x%22%5D%3D%22visible%22%7Dif(%22hidden%22%3D%3D%3Ds%5B%22overflow-y%22%5D)%7Bnode.style%5B%22overflow-y%22%5D%3D%22visible%22%7D%7D)%3Bvar%20htmlNode%3Ddocument.querySelector(%22html%22)%3BhtmlNode.style%5B%22overflow%22%5D%3D%22visible%22%3BhtmlNode.style%5B%22overflow-x%22%5D%3D%22visible%22%3BhtmlNode.style%5B%22overflow-y%22%5D%3D%22visible%22%7D)()%3B%0A
```
