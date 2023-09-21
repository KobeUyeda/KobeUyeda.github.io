---
layout: essay
type: essay
title: "Reflecting on Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2023-09-20
published: true
labels:
  - IntelliJ
  - ESLint
  - Coding Standards
  - JavaScript
---
<img width="100%" src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBw8PDxARDxIRFhAQEhcXFRYVEhgYERUPGBIWFxUXFxUZHSggGBolGxUVITMhJSkuLi4uFx81ODMuNygtLisBCgoKDg0OFxAQGi0mHiYtKy8tLystLS0tLjctLS0tLy4vLysvLSstLy0tLS0tLSsuLS8tLS0tLS0tLS0tLS0tLf/AABEIAOEA4QMBIgACEQEDEQH/xAAcAAEAAgIDAQAAAAAAAAAAAAAABgcBCAIEBQP/xABREAABAwECBwgMCggGAwEAAAABAAIDBAURBgcSITFBURMWIlNhcZKyMjQ1QnJzgYORocHRFBdEUnSiscPS0xhUVWKClLTwIzNDk7PCJKPhCP/EABsBAQACAwEBAAAAAAAAAAAAAAAEBQIDBgEH/8QAOxEAAgEBBAUKBQIFBQAAAAAAAAECAwQFESExQVFx0RITIjNhgZGhscEUFTJS4bLwBiRygqIjQmKS0v/aAAwDAQACEQMRAD8AvFERAF51u13wemml1sYcnlkOZg6RC9FQLGbaFzYqcHT/AIjubO1o5r8o/wAIWMngiZd9m+ItMKb0Y4vcs3w7yFQWlUMv3OWVvgyOH2Fd2DCevZ2NRJ/EQ/rgrx1lRz6BOlTn9UU96T9USemw7rm9k6N/hsH/AEyV3oMYkw/zIYz4Jc37cpQpF7i9pFndtknppx7lh6YFiU2MSE/5kMgH7rmu+0NXfhw6onad1b4TL+qSqsRZcuRFncVjl/ta3N++JcUOFFA/MKhg8K9vWAXeitGnf2E0TvBkafsKo+9ZyuVe84yNP+HKD+mclvwfAvtFRNPWTRkOje9pHzXFv2K0sEcIRWR5L7hOzshoym6Mto+0ajzhZxniypt9zVLLDnIy5UdeWDXbhi8iSIiLMpgiIgOLiALzoCilJhzSyVL4Scll9zJCeC467/mi/QdfIvHxhYUdlSU7uSZwOviwft9G1V8r+wXTGpSc62tZbV29+pbM9awp7ZeTp1FClnhp4fvX3mwyKqMEsM3U2TDUZToNAdpdGOT5w5NWrYrQpp2Ssa+NwcxwvDgbwQqu12OpZpYS0anqfB9ntmT7PaqdeOMdOta1+9p90RFEJIREQBERAEREAREQBUrhNaHwmrmkBvblXM2bm3M27nAv8qs7C+v+D0crr7nPG5t8J+bNyhuUfIqfJWqo88Dqf4ds/RnXevor1ft5hERajpgiIgCIiALKIvcDzEL7UdVJDI2SJxDmm8H+9I1Xcq+CLLA1yaawZcWDltx1sQc24PbcJGfNddpG1p1Hk2gr2lR9kWnLSytljOcZiD2JZrDuQ+4q3rFtOKribLGcxzOaeyY/W08v25ityeJxV53f8PPlw+h+XZu2eGlHpKH4cYT/AAVm4wn/AMiQZyP9Nh1+EdXp2X+jhVb7KGG/MZX3iNp2/Od+6PcNapypnfK90kji57ze4nSSVc3XYOefO1F0VoW18F56Npy14W3mlzcPqfl+Xq8T53rCyi6k54wvawbwknoX3s4UTjw4yeCeUHvXcvpvXjIsKlONSLjNYpmcJyhJSi8GXnY1sQ1cYkhdeO+acz2O2OGr7DqXpqhLMtKallEsDy146Lm62uGsK2MF8KIa5uT2E4HCjJ07XMOseses8rbrslZ+nDOHmt/Z2+Pb0Vjt8a3RllLye7gSNERVZYBERAEREARF8ppQxrnONzWgknYALyUBXmMq0cqWOBpzRtyneMdov5mj66ha7NrVjp55ZXaZHE3X6AexHkFw8i6yjN4vE+jWOz/D0IUtiz36X54hEXh4S246j3LJY126ZV95IuycnZ4SJYvBGyvXhQpupUfRWnXpeHue4ig2/mXiWdJyzv5l4mPpFZc2yu+eWL7n/wBZcCcooNv6l4mPpOTf1LxMfSK95tmPzux/f/jLgThFB9/MvEx9Ipv4l4mPpFeqDMHfVk+7yfAnCKD7+ZeJj6RWN/MvEx9IrNRMHfFl+7yfAm69bB23H0U2U3Ox2aRl9wLdXMRqPvVZ7+ZeJj6RWN/EvEx+krNJEepedknFxk8U9OTJ7bVoy1U7pZjndoHetZqaDye8roqIvw1kIuMMeb945l8t+cnEx9IrqLPe1mVOKl0WssEnhlsw1fvtfzq2XZUVaXNPlRxxTeTz2rLNaMsnpy0EzRQzfnJxMfSKb85OJj6RW75tZPu8nwI3y20bPNEzRQzfnJxMfSKb85OJj6RT5tZPu8nwPfl1o2eaJmuUUjmODmEtc03gg3OBGggjQojQ4VySyxxmKMB8jW358wJuUsUihaadeLdN5aNHE01bPOk8JrAs3BLDds2TDVkNl0NfoY87Hamu9R5NCnK15uU0wSw1fBkw1Rc+HQ1+l7BsOtzfWOXQKe3XUs6lBb48OHhsLOyW9/RV8ePHx2lpIvjBMyRrXsIcxwva5pvaQdYIX2VAW4REQBRjD20dwoy0HhTuyOXI0v8AJcMn+JSdVXjDtDdaoRg8GFt3Juml56o/hWE3gi0uez89ao46I9J92jzwIuiLK0ndmFDsY2il8792pkobjG0Uvnfu1lD6iqvl/wAlU/t/XEhKIi3nChFYNi4orUrKaGphNNuczA5uVK4OyTtGTmK7nxG2ztpP9534EBWSKzfiNtnbSf7zvwLp2ziitSjppqmY025wML3ZMri7JGm4ZOcoCvkREAREQBFYNi4orUrKaGphNNuczA5uVK4OyTtGTmKxbmKS1KKmmqZjTblA3KdkyuLsm/UMkX6UBX6IiAIiIDvWP2zT+Oj64VoqrrG7Zp/HR9cK0V0VzPClLf7IprxWNRbvdhERW3KISge7gxhPPQOuHDgceFGTm5XNPeu9R17Ra9k2rDVxCWB2U3WNDmu+a4aiqLXcsi1JqSUSwOudrGlrm7HDWPs1XKstthjX6Ucpeu/iT7NXlS6Lzj6buBfCKvfjCm/VW/7p/Cip/l1p+3/KPEm/G0fu8pcCb2hUthikkdojYXHluGjnOhUjUTOe973Z3PcXE7XEkk+klWPjJtHIp2Qg8KZ158W3P1i30FVsqybxZ3VwWfm6DqvTJ+S/OPggiwi8wLpyChuMXRS88v3amShmMT5Nzy/drOKzKq95fydT+39USFoiLYcUbdYr+4tnfR2+1SlaOLarEn3AofP/ANXMgJyozjM7jWj9Gf8AYuGNDuLaP0d3sWoqAIiIAiIgNusV/cWzvo7fauONTuJaPiD1guWK/uLZ30dvtXHGp3EtHxB6wQGo6IiAIiIDvWN2zT+Oj64Voqr7F7ap/HM64VoK/ul/6Ut/sittkcai3e4RZRWXKNCpmEOhZC4v0HmWymscMSHaamTiiW/AAik3wFFSfEstfh1sInhtX7vWyZ+BF/hjmZflfWJ9S8FWtaeBlHNeWtdG464zmv8ABN4HkuUWtHACqZeYXskbsvyXehxu+sqHks+g2S9LI6caafJwSXSy0dujzREkX2q6KWF2TNG5h2FpF/Nfp8i66yUSwc01igodjE+S+d+7UxUOxifJfO/drPDIq70ljZZrd+pELREXhyQW1WJPuBQ+f/q5lqqtqsSfcCh8/wD1cyA9DGh3FtH6O72LUVbdY0O4to/R3exaioAiIgCIiA26xX9xbO+jt9q441O4lo+IPWC5Yr+4tnfR2+1ccancS0fEHrBAajoiIAiIgO/YfbVP41nWCtFVdYnbVP41nWCtJXV2Swpy3+yI9aPKkjCyiK1px5WZXWqryOhHTr7AuL9B5llLr821S4aUVE9DLy+BovQuRcRzrOz5tGURdWvqmwRPlfoYL+c6gOUm4LW2ksXoMUm2ktJGMObRBDaYXG+5z/8Aq32+hQiWhYdGY8mj0Lu1M7pXukcby8knnPsXzXJVLfVlWdSEmti7NWK0dujSzsbNQVCkoLv36+G5HlS0LhouPqKguMZpHwa8Ef5n3asxyr3Gp8k8792ruxW+pVahNLPXo7d3kiBeMnzElu9UQBERWZzgW1WJPuBQ+f8A6uZVdg1iWkrqOnqhWsYJ4w/JMBJbfqvyxerrwGsA2ZZ8FG6QSGHdOGG5IOXM+Tsbzddl3adSA6uNDuLaP0d3sWoq3Lwrsk11DU0rXhhnjLMoi8Nv13Xi9UdhJiVkoaOoqjWseKeNz8kQEF12q/LNyAqVduz6GWolZDAxz5ZHZLWNF7i7+9epddjS4gAEkm4AaSdQAWzWKbF62y4RPUNBr5m8LQRCw59zadZ+cRrzDMLyBrRNE5jnMe0te0kOa4EOa4G4gg5wQdS+K2rw0xZWfarjK8OiqdcsVwL7hcN0aRc/nzHMBfcLlGLDxE0kMzX1VS+oY03iMRCJrrtTzlOJHNcgJ1i5hdHY9nNcLj8FjN2vhNyh9q6+Nd4bYloEm4bjd5S9oHrIUqY0AAAXAaANAVWf/oK3mQ2e2jBG61j2kjWII3B5cdnDDANufYgNckREAREQHfsLtqn8azrBWmqtsPtqn8azrBWkrm64cqL2YkS12hUY5fU9HHh2mERYV9FHPSbebC+lK2+Rg2uA9LgvmuzZIvngG2VnWC2aFiYLOSRfSIi4I7PEKEYa2lluEDTwWZ38ryMw8gPr5FKLXrm08T5DpAuaNrzoH96gVWMjy5xc43ucSSdZcTeSqi97TyYKjHS9O7Z3vyLS6bNypus9CyW/8LzMLCysLnjomcHKvcavyTzv3asJyr3Gr8k8792rm7etj3+jKa8eql3eqIAiIuhOeNosXeFVmQ2RQxy1tGyRkDQ5j6iNr2uz5i0uvBUj362R+0KH+ai/EtOkQG4u/WyP2hQ/zUX4lHcYOFdmTWTXxxV1G+R9O8Nayojc9ziMwDQ68lauIgCt/FzjgdSMZS2kHyQNAayZueWNugB479o2jhC7vs11QIgNy7IwmoaxodS1UEl40NkGWPCYeE08hC79RWRRtLpJI2NGkueGgDnJWkqIDaDCrG9ZdE1wgkFTP3rYTfFfdmLpuxyfByjyLXXCO3qi0amSpqn5UjzqzMYwdixg1NH/ANN5JK8lEAREQBERAd6xu2qfx0fXCtRVXY3bVP46PrhWmugujq5b/ZFLefWLd7sLCIrlFUzC79gC+spRtnj/AORq89elgyL66k8fH6ntPsWU/pe5+gp9ZHevUvNERcGdiRHDiCZwYQL4WDPdpDzrcNl2vnUOVvqH4QYL33yUw5XR6udn4fRsVHeN3zlJ1oZ7Vr7uHqXd3XhCMVRqZbHq7+JEVhCLjcdI07QUVEXrODlXmNN2elGwSevc/crDcq1xlPynU55ZPRwFf3VT5UnLYvXLiU15dVLu9UQhERXZzwREQBERAEREAREQBERAEREAREQHesbtqn8dH1wrTVWWN21T+Oj64VpLorm6qW/2RR3p1sd3uwsIsK6SKoyvVwSbfX0njW+rOvKXtYFi+0abwz6muKwr5Upv/jL0ZlQ62G9epdSIi4Y7AIiIeHg27g/HUAubcyb52p3I736edQSrpZIXlkjS0jUdm0HWOVWyuhadmRVLMmQZxocOyaeQ+xVdtu6Nbpwyl5Pf29viWdivKVHCE84+a4rs8NhU9U/JY48nrVbYw/k3nPu1Z+FdnvpXNieQcrhNcNbdAzaubkVYYw/k3nP+imXbZ5UrK3JYNv0y4vvJNvqRnSbi8Vl6ohiIrjsjEY+ppoJ/hzW7vCyTJ+DE5OWwOuv3TPdfpUgoynEV3fo+v/aDf5U/mp+j6/8AaDf5U/moCkUV3fo+v/aDf5U/mp+j6/8AaDf5U/moCkUV3fo+v/aDf5U/mqLYw8V7rGpY6g1Qm3ScRZIhLLr43vyr8s/Muu5UBXSIiAIiIAiIgCIiA71jds0/jo+uFaRVW2P2zT+Oj64VorpLl6qW/wBkUV69bHd7swsrCyrpFSwvewCF9pU38f8AwuUfUixfC+0qfkEh/wDS8e1abV1FT+mXozbZuup/1R9UXIiIuHOuCIiAIi6lpVQghllOiNjnc9wJuQFUYb12718xB4MV0bf4Oy+uXqscYXybzn3amT3FxJcb3E3k7Sc5KhuML5N5z7tTqkeTTaLOuuTRcV2eqIYr9sLHZZ1PSUsD4awvggjjcWsiyS5kbWki+S+68KgkUErDYv4+rK/V67oRfmp8fVlfq9d0IvzVroiA2L+Pqyv1eu6EX5qfH1ZX6vXdCL81a6IgNi/j6sr9XruhF+aoZjWxlUVsUUVPTxVDHsqGyEytYG5IjkbcMl5N97xq2qp0QBERAEREAREQBERAd6x+2afx0fXCtFVdY3bNP46PrhWiukuXqZb/AGRQ3r1sd3uwiLirtFSFKMWzb7QZyMefqXe1RhS3Fk2+vPJE4+sD2qPbcrPU/pZIsSxtFPei2ERFxB1gREQBRLGRW7nRiMaZ5A3+AcMn0ho8qlqq7GXW5dWyIHNDHn8N/CP1QxbaEeVNG6hHGaIgo1hlZk9RuG4sysjLvzgXX5F2k8hUkWVYTgprBkyphJclla72q3iT0me9N7VbxJ6TPerJRavhIbWR+ZjtZW29qt4k9JnvTe1W8Sekz3qyUXvwcNrMXSiVtvareJPSZ703tVvEnpM96shZXvwcNrMXTRW29qt4k9JnvTe1W8Sekz3qygwrkG3LL4GG1kWrWpwTweL/AH3Fab2K7iT0mfiTexW8Semz8SssrC2q7qb1y8VwK922a1IrTe3W8Sekz3pvbreJPSZ71ZSwVtV10nrl4rga3eFVal58Stt7lbxJ6TPem9yt4k9JnvVkrCzVz0Hrl4rgYO8quxeD4lb73K3iT0me9N7dZxJ6bPerHWFmrlofdLy/8mDvStsXg+JArMsGrZPC90RDWysJOU3MA8XnSp6sLKsLJZIWaLjBvN454eyRCtNolXkpSSyWGQXFFlTCKwpjisF9ZJyQO67B7VDFPMV9DK2eWVzHiN0Ra1xaQ1xL2nMTpzN1KJeElGzVMdhLsCxtEMP3kWWiIuKOqCIiAwTcqKtes+EVE03GSOI8C/gjyNuCtvDCu3ChncDwnNyG7cp5ybxzXk+RUyptkjk5EmzrDFhEWVOwNzZhF3bOsmpqDdBE942gXMHO83NHpUusvF083GqlDR82PO7puFwPkKwnVhD6mapTSIISvYszBisqbjHC4MPfycBl23PnI5gVaNlYNUlLcYom5Y793CffyE6PJcvYUadt+xeJqdTYQOzsXUYF9TM5xu0RgNaD4RvLvQF4GEGCU9Je9o3SAd+0cJo/fbq59HMrbRaFaqmOLePYaKkeWsGUIuJVm4Q4ERT3yU90Uukt/wBJx5h2J5R6FXVoUM1PIY5mOY8ajoI2tOhw5QrWz1YVdGnZrKutTlDTo2nWK4rKwp8UQpMwiwUW+KNMmFhZWFtRqbC4rKwVtSNbZlcV7Fk4NVlVcY43ZB792Zl20E9l5L1M7IxdQsudUvMh+a29rOYu7I+pRq9uoUMpyz2LN/jvwJFGx1qucVlteS/O9YlcU1PJK4MiY57joa1pc70BS6ycXtTLc6oc2Fuzsn3cwNw9PkVk0NDDA3IhjYxuxrQL+U7TyldtU1e+6ksqUcFteb4LwZaUbppxzqPF+C4ngWTgnR0txZHlPHfv4Rv2gaG+QL30RVFSrOpLlTbb7SzhCMFhFYLsCIi1mYREQEAxp1nBp4BrJkd5Bks+1/oUDpKSWZ2RCx73bGtJI57tA5Srfr8Gaaeczzhz3ZIa1pddG1reQXX5yTnOterTU0cTQyNjWNGhrWgN9AUuFoVOCilizcqijHBFa2Xi/qpLjO5kTdnZyegG4enyKW2ZgXQwXEx7q8d9Lwvq9j6lJEWqdoqS1+GX5MHNs4MaAAAAANAGi5c0RaTAIiIAiIgC6VpWdDUxmOZgc3VfpB2tOkHlC7qL1Np4o8aTyZVeEeBM9PfJT3yxbLv8Rg5QOyHKPRrUSvWwKi2EeB9PVgvZdHOc+UBwXn99uvnGfn0K2st5YYRrePHiVtosOOdLw4FTrC79sWRPRvyJ2Fux2ljhta7XzadoX1snByrq7jFE7IPfu4LLtuUey8l6vFUgo8vlLDbjkVLhJy5CTx2azylzp4HyODI2ue86GtaXO9AVjWTi8ibc6qeXn5rb2t5i7sj5LlL6Gghp25EMbGN2NaBfynaeUqBWvelDKmuU/BcfLvJlK7Kks5vBeL4ebK1sjF/Uy3GcthZs7J/oBuHlPkU0snBGipri2PLeO+k4Rv5B2I8gUhRVNe8a9bJvBbFl+X3ssqNio0s0sXteb/HcERFBJYREQBERAEREAREQBERAEREAREQBERAEREAREQBERAeHhd2u3x0XXC9sIi2y6qO+XsYx+p7l7mURFqMgiIgCIiAIiIAiIgCIiA//2Q=="/>
<h1>Coding Standards are Needed</h1>
Creating a coding standard can be hard some say. How much spaces should my indent by? Some people only use one space, others use more. What should be my format when creating a variable? Some say you should use camel case while other rather use use an underscore for any spaces. The truth is that this should not matter as long as you stick with a standard that you pick.

Coding standards are just a way for people to format code that makes reading it easy, and makes it easy to expand upon the code if need be. If I didn’t create a standard of function names, it becomes a lot harder for any one who tries to use any of the function in the future. Even if someone understands a language very well if the coding standard is all over the place, even they will struggle using what you have written. The best coding standards are ones where even if you are new to the language you can easily tell what should be happening.

The goal of any coding standard is that once someone is able to sees your format it shouldn’t change at all. If it does this is what could lead to confusion. Now as I said as long as you stick with a standard this usually does not matter, but what if you are working with a group of people? This is when issues can arise if you don’t all adhere to the same standard as each other. What if some people in your group use a different variable format, or if they have a different indent system? Well in the best case scenario your code just becomes harder to code in, and in the worst case scenario the code does not work at all.
Example (bad coding standard):

```js
function notCorrectCode (value) {
	if (value === ‘1111’) {
	return false;
	}
return true;
}
```

Example (good coding standard):

```js
function CorrectCode (value) {
	const Code = ‘1111’
	if (value === Code) {
		return true;
	}
	return false;
}
```

s you can see from the examples the second example becomes a lot easier to read. If I was to give you the second function vs the first function you can tell what its doing just by the name of the function. Then I basically label any constant values with a variable so people can have an understanding of what the value is. From their the indents are the same through out the functions making it easy to see what should happen in this function. Now the first one does something very similar to what the second function did, but it does the opposite only returning true if the value entered is not the code. Now while these functions basically does the exact same thing, it takes a little bit more time to understand what this function may be doing. To make it worse, in the function I just put an if statement that compares the value to a constant value. If someone was to look at that they may be confused why we are comparing the value to a string of 1s. Basically a good coding standard can have a major effect to how people will read your code.

Now IntelliJ helps us out with making good coding standards by verifying we are adhering to the coding standards that are set. To do this we utilize ESLint to state our coding standards, and then if we don’t follow those coding standards then IntelliJ will highlight and warn us about breaking coding standards. Very similar to how Word, or Google docs highlights any misspellings or grammar issues in an essay.

While using ESLint in assignments and WODs I started to find out that while ESLint does help make sure we follow a standard. The issue comes when it can’t detect the libraries that you have imported from another file. In many assignments I keep getting errors that it has not clue what the underscore library comes from. This makes sense since this library is only ever imported on the HTML which does not run until we open it in a browser. So while I have not received any errors from coding standards I have received many warnings that I have not defined what the underscore library was, but when I run HTML I don’t have any issues. ESLint is very helpful and useful making sure we stick to a standard, but until we start importing the underscore library through node package manager (NPM) this error will persist which is one downside considering all the other benefits that comes with ESLint.