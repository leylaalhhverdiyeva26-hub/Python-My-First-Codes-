# Python-My-First-Codes-
Python dərsləri zamanı yazdığım bütün tapşırıqlar və kiçik layihələr
## 📝 Dərs 1: Stringlər (Mətnlər) və Onlarla İşləmə

Bu repozitoriyadakı Python öyrənməyə başladığım ilk dərslərdən biridir və **string (mətn)** tipli məlumatlarla necə işləməli olduğumuzu göstərir.

Buradakı kiçik kod parçaları ilə hansı mövzuları praktikada öyrəndim:

### Nəyi öyrəndim?

1.  **Mətnləri Birləşdirmək:**
    * Bir neçə mətn dəyişənini (`mesaj`, `mesaj2`) götürüb `+` operatoru ilə onları necə bir cümləyə çevirməyi öyrəndim.
2.  **Mətnin İçində "Gəzmək":**
    * **İndeksləmə:** Mətnin istənilən simvolunu mövqeyinə görə necə çıxaracağımı (məsələn, `mesaj[0:4]`) öyrəndim.
    * **Tərs İndeksləmə:** Mətnin sonundan geriyə doğru saymağı (məsələn, sondan ikinci hərfi almaq üçün `mesaj[-2]`) tətbiq etdim.
    * **Mətnin Tərs Çevrilməsi:** `[::-1]` kimi sehrli bir üsulla bütün mətni asanlıqla tərsinə çevirməyi bacardım.
3.  **Mətnin Formatlanması (Dəyişdirilməsi):**
    * Bütün hərfləri böyütmək (`.upper()`), kiçiltmək (`.lower()`), və ya yalnız ilk hərfi böyütmək (`.capitalize()`) kimi hazır metodları istifadə etdim.
4.  **Mətnin Yoxlanılması:**
    * `startswith()` və `endswith()` metodları ilə mətnin müəyyən bir hissə ilə başlayıb-bitmədiyini yoxladım. Bu, "True" (doğru) və ya "False" (yanlış) cavabını verir.
5.  **Ölçmələr:**
    * `len()` funksiyası ilə dəyişənlərin (stringlərin) ümumi simvol sayını tapmağı öyrəndim.
    * `"Mətn" * 10` kimi sadə bir əməliyyatla mətnin bir neçə dəfə təkrarlanmasını gördüm.
**Müvafiq Kod Faylı:** [03_String_Indeksleme.py](03_String_Indeksleme.py)



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



