# Python-My-First-Codes-
All the assignments and small projects I wrote during my Python lessons.
## 📝 Lesson 1: Strings and Working with Them

This is one of the first lessons where I started learning Python in this repository, demonstrating how to work with **string** data types.

Here are the topics I learned in practice with these small code snippets:

### What Did I Learn?

1.  **Concatenating Strings:**
    * I learned how to take a few string variables (`mesaj`, `mesaj2`) and turn them into a single sentence using the `+` operator.
2.  **"Navigating" Within a String:**
    * **Indexing:** I learned how to extract any character of a string by its position (e.g., `mesaj[0:4]`).
    * **Reverse Indexing:** I practiced counting backward from the end of the string (e.g., `mesaj[-2]` to get the second-to-last letter).
    * **String Reversal:** I managed to easily reverse the entire string using a "magic" method like `[::-1]`.
3.  **String Formatting (Modification):**
    * I used built-in methods like making all letters uppercase (`.upper()`), lowercase (`.lower()`), or only capitalizing the first letter (`.capitalize()`).
4.  **String Verification/Checking:**
    * I checked if a string starts or ends with a specific part using the `startswith()` and `endswith()` methods. This returns a "True" or "False" answer.
5.  **Measurements and Repetition:**
    * I learned how to find the total number of characters in variables (strings) using the `len()` function.
    * I saw how to repeat a string multiple times with a simple operation like `"Mətn" * 10`.

**Müvafiq kod faylı
[03_String_Indeksleme.py](03_String_Indeksleme.py)



## 🔢 Dərs 2: İntegerr, Hesablamalar və Müqayisələr

Bu dərsdə Python-da əsas rəqəmlərlə necə işləməyi öyrəndim.

 1. Rəqəmlər və Tiplər 

* **int (Tam Ədəd):** Tam rəqəmlər. Məsələn, `5`, `8`.
* **float (Kəsr Ədəd):** Kəsr hissəsi olan rəqəmlər. Məsələn, `9.5`, `-2.17`.

**Tip yoxlaması:** `print(type(number1))` əmri Python-a sual verir: "Bu dəyişən nə tipdədir?"

## 2. Riyaziyyat Əməliyyatları və Qısa Yollar 

| Operator | Nə İş Görür? | Nümunə 
| `**` | Qüvvətə yüksəldir. | `5**100` |
| `//` | Tam Bölmə. Bölmənin kəsr hissəsini atıb, sadəcə **tam hissəsini** qaytarır. | `14 // 6` = 2 |
| `*=` | Qısa Təyinat. Dəyişənin özünü vurub nəticəni yenidən ona təyin etmək üçün qısa yoldur. | `l *= 5` (yəni `l = l * 5`) |

### 3. Daxili Köməkçi Funksiyalar 

Bu funksiyalar kodumuzda çeviklik yaradır:

* **`abs()`:** Rəqəmin mənfi olub-olmamasına baxmayaraq, həmişə onun **mütləq müsbət dəyərini** (modulunu) qaytarır.
* **`round()`:** Kəsr ədədləri yuvarlaqlaşdırır. Məsələn, `9.5`-i `10`-a çevirir. Onluq hissədən neçə rəqəm qalmasını da göstərə bilərik (məsələn, 3 rəqəm: `round(number, 3)`).

### 4. Tip Çevirmə (Type Casting) 

Bəzən bir tipli dəyəri digərinə çevirmək lazım gəlir:

* **`int()`:** Bir sətiri (`"100"`) və ya kəsr ədədi **tam ədədə** çevirir.
* **`str()`:** Hər hansı bir rəqəmi (və ya başqa dəyəri) **sətirə** çevirir.

### 5. Müqayisə Operatorları (Sual Sorğulamaq) 

Bu operatorlar iki şeyi müqayisə edir və həmişə bizə **"Hə" (True)** və ya **"Yox" (False)** cavabını qaytarır.

| Operator | Mənası |
| `==` | Bərabərdirmi? |
| `!=` | Bərabər deyilmi? |
| `<` / `>` | Kiçikdirmi / Böyükdürmü? |
| `<=` / `>=` | Kiçik və ya Bərabərdirmi / Böyük və ya Bərabərdirmi?


**Bu Dərsə Aid Kod:** [İnteger.py](İnteger.py)



