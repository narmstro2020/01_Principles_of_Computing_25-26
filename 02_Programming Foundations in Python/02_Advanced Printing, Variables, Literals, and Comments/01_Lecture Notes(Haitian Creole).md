# Nòt Leson – Prensip Enfòmatik
## Sijè: Python – Enpresyon Avanse, Varyab, Literal, ak Kòmantè

---

## 🧠 Seksyon 1: Varyab

### 🔤 Kisa yon Varyab ye?
- Yon varyab se yon **non** ki refere a yon **valè** ki estoke nan memwa.
- Varyab pèmèt pwogram yo sonje epi itilize enfòmasyon ankò.

### ✅ Sentaks
```python
non = "Jordan"
laj = 16
wotè = 5.9
```

### 🧠 Règleman pou Nonmen
- Dwe kòmanse ak yon lèt oswa tirè anba (`_`)
- Ka genyen lèt, chif, ak tirè anba
- Pa ka sèvi ak yon mo kle Python (`if`, `print`, `while`, elatriye)
- Pa ka genyen espas

---

## 🔢 Seksyon 2: Literal

### 📘 Kisa yon Literal ye?
Yon literal se yon **valè fikse** ki itilize nan kòd Python.

### 🧱 Kalite Literal

| Kalite     | Egzanp          |
|------------|-----------------|
| Chenn      | `"bonjou"`      |
| Antye      | `42`            |
| Desimal    | `3.14`          |
| Boulenn    | `True`, `False` |

### ✅ Egzanp Kòd
```python
salitasyon = "Bonjou!"
ane = 2024
pi = 3.14159
aktif = True
```

---

## 💬 Seksyon 3: Kòmantè

### 📗 Kisa yon Kòmantè ye?
- Yon kòmantè inyore pa Python.
- Sèvi pou eksplike sa kòd ou a ap fè.

### ✅ Sentaks
```python
# Sa a se yon kòmantè
non = "Jordan"  # Sa mete non an
```

- Sèvi ak kòmantè pou:
  - Dekri seksyon kòd
  - Dezaktive yon liy tanporèman
  - Eksplike poukisa yon bagay fèt

---

## 🖨️ Seksyon 4: Enpresyon Avanse

### 🔹 `print()` ak Vigil
```python
print("Non:", non)
print("Laj:", laj)
```

### 🔹 Konkatènasyon Chenn
```python
print("Non: " + non)
```
- Ou **dwe** itilize `+` sèlman ak varyab chenn.

### 🔹 f-Strings (Chenn Fòmate)
```python
print(f"Non: {non}, Laj: {laj}")
```
- Rekòmande nan Python 3.6+

---

## 🧪 Kòd Egzanp

```python
# Sove kèk enfòmasyon pèsonèl
non = "Maya"
klas = 10
gpa = 3.8
materya_favori = "Matematik"

# Enprime nan 3 fason
print("Non:", non, "| Klas:", klas, "| GPA:", gpa)
print("Non: " + non + " | Materya Favori: " + materya_favori)
print(f"{non} nan klas {klas} epi li renmen {materya_favori}.")
```

---

## 🎯 Vokabilè Kle

| Tèm       | Definisyon |
|-----------|------------|
| Varyab    | Yon valè ki gen non ki ka chanje |
| Literal   | Yon valè fikse nan kòd la |
| Kòmantè   | Yon liy inyore pa Python, itilize pou eksplike kòd |
| f-string  | Yon metòd fòma ki itilize `{}` pou mete valè nan chenn |

---

## 📝 Travay Kat Biyografi

Mande elèv yo pou yo kreye yon pwogram Python ki:
- Itilize 5 varyab (egzanp: non, laj, pasyon, travay rèv, manje pi renmen)
- Enprime yon “biyografi” nan twa estil fòma
- Mete omwen 3 kòmantè

**Egzanp Rezilta:**
```
Non: Sasha
Laj: 15
Travay Rèv: Devlopè Jwèt
Pasyon: Desen
Manje Pi Renmen: Sushi
```

---

## ❓ Kesyon Soti

**Mande elèv yo:**
1. Kisa yon varyab ye?
2. Kisa k rive lè ou bliye mete siy sitasyon bò kote yon chenn?
3. Ki fason ou pi renmen pou itilize `print()`?
