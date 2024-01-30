# 🦉 TSS 2024 (Windows Version) 🦉

## Credit:
<ul>
  <li>Original Codebase: https://github.com/SUITS-Techteam/TSS_2024</li>
  <li>Windows TSS Fix: https://github.com/BenRubin1</li>
</ul> 

## Requirement
### Browser: 
Chromium browsers: Chrome/Brave
<div>Firefox does not work</div>

### GCC Compiler Installation (Windows): 
1. Follow [this video](https://www.youtube.com/watch?v=k6juv3mIr9o)
2. Check gcc version,
```
gcc -v
```
### GCC Compiler Installation (Mac): 
1. Install gcc via Homebrew:
```
brew install gcc
```
2. Check gcc version,
```
gcc -v
```

## Running TSS Server
### 🪟 Windows:
1. Navigate into the directory /Windows and build
```
./build.bat
```
2. Run the server locally (we receive bind() errors if not ran locally)
```
./server.exe --local
```
3. Type the IP address printed by the server into a web browser
4. TSS Ready!
