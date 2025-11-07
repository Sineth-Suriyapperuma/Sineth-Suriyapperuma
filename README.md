<h1>Sineth Suriyapperuma 👨🏻‍💻</h1>
<p>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=Sineth-Suriyapperuma" alt="visitor badge">
  <a href="https://github.com/Sineth-Suriyapperuma?tab=followers">
    <img src="https://img.shields.io/github/followers/Sineth-Suriyapperuma?label=Followers&amp;style=social" alt="GitHub followers">
  </a>
</p>

<img align="right" alt="GIF" height="300px" src="https://octodex.github.com/images/daftpunktocat-thomas.gif">

```python 
💻 Student Developer | Learning to build smart systems & appealing projects
```

<h4>📚 ICT in the field of Management | 🌍 From LK</h4>


---

### 🧠 About Me  
🚀 Passionate about exploring the digital world and creating systems that combine logic and creativity.  
🎯 Aspiring to become a **Professor in Computer Science** one day.  
🧩 I’m currently learning **Python**, **C++**, and **Web Development** while working on small projects.  
⚡ Fun Fact: I am an **Analytical Thinker**.  

---

### 🧰 Languages & Tools

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white"/>
</p>

---

### 🧩 Featured Project — Text Encryptor (Python)
> A simple encryption script that shifts ASCII characters and converts them into binary for fun experimentation.


```python
import os
def bintodec(n):
    decimal=0
    power=0
    while n>0:
        digit=n%10
        if digit==1 or digit==0:
            decimal+=digit*(2**power)
            n=n//10
            power+=1
    return decimal

def tb_en(text):
    char=[]
    decimal=[]
    for c in text:
        char.append(c)
        decimal.append(ord(c))
    binlist=[]
    for val in decimal:
        hold_c=(val+10)%128
        binary=format(hold_c,'08b')
        binlist.append(binary)
    chrt=''
    chrt_list=[]
    for i in range(len(char)):
        bin_str=binlist[i]
        bin_dec=bintodec(int(bin_str))
        if 0 <=bin_dec<= 128:
            ascii_chrt=chr(bin_dec)
        chrt_list.append(ascii_chrt)
        chrt+=ascii_chrt
    for c in range(len(char)):
        display=print("  ",char[c]," | ",binlist[c],"| ",chrt_list[c])
    print()
    print("Encrypted values : ",chrt)

print()
line=input("Enter Text : ")
print()
print(" Char | shift_bin | shift_Char ")
print("------|-----------|------------")
tb_en(line)
os.system('pause')


```

<p>
  <em>
    This project deepened my understanding of 
    <b>binary</b>, <b>ASCII</b>, and <b>modular arithmetic</b> in Python — 
    turning logic into creativity through code.
  </em>
</p>

<hr style="border: 0; height: 2px; background: linear-gradient(90deg, #00ffff, #8a2be2, #ff00ff); border-radius: 5px;">

<!-- 🚀 Current Interests -->
<h2>🚀 Current Interests</h2>

<p style="font-family: 'Courier New', monospace; line-height: 1.8; color: #c9d1d9;">
  🧠 <b>Artificial Intelligence</b><br>
  🌐 <b>Web Design & Development</b><br>
  ⚙️ <b>Building Custom Operating Systems</b><br>
  🎮 <b>Game Development</b>
</p>

<hr style="border: 0; height: 2px; background: linear-gradient(90deg, #ff00ff, #8a2be2, #00ffff); border-radius: 5px;">

### 📊 GitHub Stat

<table align="center">
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=Sineth-Suriyapperuma&show_icons=true&bg_color=0D1117&title_color=00FFFF&text_color=FFFFFF&icon_color=00FFFF" alt="GitHub Stats">
    </td>
    <td>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sineth-Suriyapperuma&layout=compact&bg_color=0D1117&title_color=00FFFF&text_color=FFFFFF" alt="Top Languages">
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://streak-stats.demolab.com/?user=Sineth-Suriyapperuma&theme=tokyonight&hide_border=true">
    <td>
      <img src="https://readme-jokes.vercel.app/api?theme=dark" alt="Jokes Card">
    </td>
  </tr>
</table>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=sineth-suriyapperuma&bg_color=0D1117&color=00FFFF&line=00FFFF&point=FFFFFF&area=true&hide_border=true" alt="GitHub Activity Graph">
</p>


<hr style="border: 0; height: 2px; background: linear-gradient(90deg, #ff00ff, #8a2be2, #00ffff); border-radius: 5px;">

### ⚡ <b><i>"Code. Learn. Evolve."</i></b><br><br>
<p>
  👨‍💻 <b>Credit:</b> <a href="https://github.com/Sineth-Suriyapperuma">Sineth Suriyapperuma</a> <br>
  🕒 <b>Last Edited on:</b> 07/11/2025
</p>

