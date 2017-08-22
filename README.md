# vecterminus
Vectorized Terminus Font

The original Terminus font is a set of bitmap fonts designed for prolonged programming. Using Fontforge's python API, each bitmap pixel has been vectorized. This means that the glyphs still retain their true shape and proportions, regardless of the font size, but look perfect at their intended design size.

For most applications, like Word, LibreOffice, or regular text editors like Atom, the following settings are recommended for ideal appearance (assuming 96dpi screen resolution, 72pt=96dpi or 25% reduction from px to pt):

Font Design Size | Point Size
:---:|:---:
12px | 9pt
14px | 10.5pt
16px | 12pt
18px | 13.5pt
20px | 15pt
22px | 16.5pt
24px | 18pt
28px | 21pt
32px | 24pt

If used in Notepad++ (like I usually do), the above settings don't work quite right for some reason. Here are the settings that I discovered by trial and error to work well (again, assuming 96dpi screen):

Font Design Size | Point Size
:---:|:---:
12px | 11pt
14px | (No good match)
16px | 14pt
18px | (No good match)
20px | (No good match)
22px | (No good match)
24px | 20pt
28px | (No good match)
32px | 26pt


These fonts are licensed under SIL OFL under the unique name "Vecterminus". See http://scripts.sil.org/OFL for license details.
