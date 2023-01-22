# vs code install

## links

-  [vscode下載](https://code.visualstudio.com/docs/cpp/config-mingw  "Title") 
-  mingw64下載 (可自行挑選下載方式)
   - [路徑1 - google drive](https://drive.google.com/file/d/1OVHKpgJB-Uqvbm7TLBlhwjtZc6Z0HCG8/view?usp=sharing "Title")
   - [路徑2 - sorceforge](https://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win64/Personal%20Builds/mingw-builds/8.1.0/threads-win32/seh/x86_64-8.1.0-release-win32-seh-rt_v6-rev0.7z/download "Title")

## windows powershell(cmd)

- `cd <folder> ` 進入folder
  - ex: `cd Desktop`
- `cd ..` 退到上一步的folder

- `mkdir <name>` 創建一個新的folder 
  - ex: `mkdir projects` 創建一個名叫`projects`的folder 

## vscode 

- `ctrl+shift+p` vscode搜尋欄

- `g++ <檔名>.cpp -o <名字>` 編譯(compile) `<檔名>.cpp`並且創建執行檔`<名字>.exe`

  - ex: `g++ main.cpp -o main` 編譯`main.cpp`並且將其程式的執行弄到`main.exe`

- `.\<檔名>.exe` 執行code

  - `.\main.exe`


- ```c++
  // tescode
  #include <bits/stdc++.h>
  int main(){
      std::cout<<"hello world!";
  }
  ```

## 常見問題

  - 如果找不到 bin 資料夾?
    - 試試 [google drive](https://drive.google.com/file/d/1OVHKpgJB-Uqvbm7TLBlhwjtZc6Z0HCG8/view?usp=sharing "Title") 下載的方案   
  - 如果出現類似已下指令 可能代表你忘了  `save` 

```
c:/mingw/bin/../lib/gcc/mingw32/6.3.0/../../../libmingw32.a(main.o):(.text.startup+0xa0): undefined reference to `WinMain@16'
collect2.exe: error: ld returned 1 exit status
```

- 如果有 `save` 解果出現以下指令 代表你可能忘記打 `int main ()`  或是打錯

```
C:/mingw64/bin/../lib/gcc/x86_64-w64-mingw32/8.1.0/../../../../x86_64-w64-mingw32/lib/../lib/libmingw32.a(lib64_libmingw32_a-crt0_c.o):crt0_c.c:(.text.startup+0x2e): undefined reference to `WinMain'
collect2.exe: error: ld returned 1 exit status
```


<mark>hi</mark>

