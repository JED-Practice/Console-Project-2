# Inventory Management

## Proyekt haqqında

Sistemin əsas məqsədi, anbarların idarə edilməsini rahatlaşdırmaqdır. Sistem istifadəçilərə məhsulların detallarına baxmağa, onları idarə etməyə və reportlar hazırlamağa kömək etməlidir. Proyekt bir konsol aplikasiyası olmalıdır və database üçün EF Core istifadə edilməlidir

## Əsas özəlliklər

1. **Login, Register:**

   - Anbardakı məlumatları qorumaq üçün bir login, register sistemi olmalıdır. İstəyə görə rollar da əlavə edilə bilər

2. **Məhsul Menecmenti:**

   - Məhsulları daxil etmək, silmək, update etmək
   - Məhsulları kateqoriyalaşdırmaq, beləcə xüsusi kateqoriyalara görə reportlar əldə etmək

3. **Tədarükçü Menecmenti:**

   - Tədarükçülərin idarəsidi də olmalıdır. Onların məlumatlarının əlavə edilməsi, silinməsi kimi özəlliklər
   - Hər bir məhsul tədarükçü ilə əlaqələndirilməlidir ki, hansı məhsulu hansı tədarükçünün verdiyi bilinsin

4. **Məhsulların satışı:**

   - Aplikasiya məhsulların satışını təmin etməlidir
   - Hər satışın detalları ayrıca saxlanılmalıdır, tarixçə məntiqini tətbiq etmək üçün
   - Edilən satışlara görə reportlar hazırlanmalıdır

5. **Reportlama:**

   - Ehtiyyaca uyğun olaraq pdf və ya excel formatında reportlar yaradılmalıdır
   - Yaradılan reportlar isə xüsusi qovluqda saxlanılmalıdır

6. **Axtarış və ya filterləmə:**
   - Məhsullara, tədarükçülərə və ya istifadəçilərə uyğun axtarış etmək mümkün olmalıdır
   - Reportların generasiyası zamanı filterləmə dəstəklənməlidir. Məsələn istifadəçi spesifik tarixdən bu günə olan satışlarını görmək istəyə bilər
