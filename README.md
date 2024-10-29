# Lavender Night Joplin Theme

A little theme I made with the help of ChatGPT + Copilot for Joplin! Will be updating soon with better css. It's based on the Tokyo Night VsCode theme, with a bigger focus on purple/lavender elements, and being flat/minimalistic overall.

## Gallery
![image](https://github.com/user-attachments/assets/58f2dec1-edfc-4592-8bc9-b4713b533e5a)

![image](https://github.com/user-attachments/assets/c5cbf200-e6b7-4316-8e12-2957f90f0d43)

## Recent Changes
- Bullet and numbered list colouring:
![image](https://github.com/user-attachments/assets/448bf8e7-ea2c-4112-bcfb-4306eac009c3)
For some reason, getting tabbed list colours past two tabs broke a while ago, causing the starting colour to repeat again as you can see. I've made the preview follow these repeating colours too, for consistency's sake, despite the colours still working in the markdown preview.

- Thicker border under h1s:
![image](https://github.com/user-attachments/assets/11fb79f1-6752-42d5-9ec8-78faa2e95698)
Increasing the thickness of the border under h1s up from 1px to 3px is mostly a personal preference thing for myself. If you don't like it edit the following css in userstyle.css (replacing the px number with what you'd like):
```
h1 {
  color: var(--blue) !important;
  border-bottom: 3px solid var(--lavender) !important;
}
```

I've also made the same thickness/lavender colour carry over to markdown separators once again for consistency's sake, which can we edited through the following once again in userstyle.css:
```
/* Markdown separator (---) */
hr {
  border: none;
  border-bottom: 3px solid var(--lavender) !important;
}
```

## Areas to Improve
1. Rich Text Editor:
![image](https://github.com/user-attachments/assets/2261b38c-6360-4be9-a7d2-e06469c223f9)
As you can see, the rich text editor needs quite a bit of work. Namely, the big grey box, as well as lavender filling for most of the styling buttons. I've tried battling with the css here quite a bit but just can't seem to get it, so if you have any ideas please lmk or feel free to make a pr!

2. After 3.1.20:
After the new Joplin update (3.1.20), I haven't gotten around to fixing the leftmost sidebar, so hover/selected colour is still the default blue. I also haven't gotten around to fixing icon colour. However, I did fix a little bit of the areas that turned grey, such as the little area behind the new note/to-do buttons.
