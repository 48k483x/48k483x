<!-- ```javascript
const abdu = {
    education: "42",
    currentLearning: ["iOS Development", "System Programming", "Flutter", "C", "Assembly"],
    tools: "Vim + tmux",
    contact: {
        email: "abderrahmanech@outlook.fr",
        twitter: "@48k483x"
    }
};
```
```asm
section .data
    me:
        db "42", 0
        db "iOS,Systems,Flutter,C/C++,ASM", 0
        db "Vim + tmux", 0
        db "abderrahmanech@outlook.fr", 0
        db "@48k483x", 0
``` -->
```c
struct abdu {
    char *edu = "42";
    char *learning[] = {"iOS", "Systems", "Flutter", "C/C++", "ASM"};
    char *tools = "Tmux + vim";
    char *email = "abderrahmanech@outlook.fr";
    char *twitter = "@48k483x";
} me;
```
