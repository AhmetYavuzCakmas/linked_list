# linked_list
data structure linked list code

Linked List (Bağlı Liste), verilerin ardışık olmayan bellek alanlarında tutulduğu ve her elemanın bir sonrakini işaret ettiği bir veri yapısıdır.

🔹 Temel Mantık

Her eleman Node (düğüm) olarak adlandırılır ve iki parçadan oluşur:

Data (veri)

Next (bir sonraki düğümün adresi)

[data | next] → [data | next] → [data | null]


Son düğüm null gösterir.

🔹 Neden Kullanılır?

Dizi gibi sabit boyutlu değildir

Eleman ekleme / silme kolaydır

Bellek dinamik kullanılır

🔹 Avantajları

✅ Dinamik boyut
✅ Ekleme–silme işlemleri hızlı
✅ Bellek kaydırma gerekmez

🔹 Dezavantajları

❌ Rastgele erişim yok (index ile gidemezsin)
❌ Bellekte fazladan pointer alanı kullanır
❌ Arama işlemi yavaştır
