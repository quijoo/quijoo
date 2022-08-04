<h2> Hi, I'm Xuaii <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="50"></h2>
<img align='right' src="https://media.giphy.com/media/ieyl9zmCjO4b4t6qoY/giphy.gif" width="230">
<p><em>Game Dev Beginner, A Students of <a href="https://www.cqu.edu.cn/">CQU</a>
</em></p>

<p align="center">
  <a href="https://github.com/xuaii"><img src="https://github-readme-stats.vercel.app/api?username=xuaii&hide_border=true&show_icons=true" alt="edisonlee55's github stats"></a>
  
### <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> A gift for you...  

```c
struct ListNode *getIntersectionNode(struct ListNode *headA, struct ListNode *headB) {
    if (headA == NULL || headB == NULL) {
        return NULL;
    }
    struct ListNode *pA = headA, *pB = headB;
    while (pA != pB) {
        pA = pA == NULL ? headB : pA->next;
        pB = pB == NULL ? headA : pB->next;
    }
    return pA;
}
```

---
  
