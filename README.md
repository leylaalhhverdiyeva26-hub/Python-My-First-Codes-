# Python-My-First-Codes-
Python dərsləri zamanı yazdığım bütün tapşırıqlar və kiçik layihələr
## 📝 Dərs 1: Stringlər (Mətnlər) və Onlarla İşləmə

Bu repozitoriyadakı `03_String_Indeksleme.py` faylı, Python öyrənməyə başladığım ilk dərslərdən biridir və **string (mətn)** tipli məlumatlarla necə işləməli olduğumuzu göstərir.

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

---

**Müvafiq Kod Faylı:** [03_String_Indeksleme.py](03_String_Indeksleme.py)
