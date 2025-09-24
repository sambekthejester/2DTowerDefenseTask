2D Tower Defense Prototype On 3D World

Bu proje, KFA Entertainment için hazırlanan Tower Defense prototipi çalışmasıdır.  
Amaç: Unity’de 3D ortam içerisinde 2D sprite  kullanarak temel oyun döngüsünü kurmak.

 
https://github.com/sambekthejester/2DTowerDefenseTask

Özellikler

Oyuncu
-  WASD  hareket.
- Hem yakın dövüş (AOE melee) hem de uzak saldırı (auto ranged) yapabilir.
  - Melee saldırı oyuncu merkezli dairesel alan etkili hasar.
  - Ranged saldırı menzil içindeki en yakın düşmana otomatik mermi gönderir.
  - İki saldırı için ayrı cooldown’lar.
- Can kaybedince I-frame (geçici ölümsüzlük).
- Ölünce Game Over ekranı açılır.

Düşmanlar
- Wave tabanlı spawn sistemi
- Düşmanlar path üzerindeki waypointleri takip eder.
- Düşmanlar ScriptableObject (LevelSO) ile tanımlanır.
- Her düşmanın kendine ait: HP, Hareket hızı, Saldırı gücü / menzili
- Hem melee hem  de ranged düşman desteklenir.
- Düşman öldüğünde altın kazandırır.
- Boss düşmanlar (daha yüksek HP ve hasar).

Wave Sistemi
- Wave’ler ScriptableObject (LevelSO) ile tanımlanır.
- Dalga başladıktan sonra otomatik countdown başlar.
- Countdown sırasında skip button ile dalga erkenden çağrılabilir.
- Düşmanlar path'in sonuna geldiklerinde BaseHP düşer.

UI
- Gold, Player HP, Base HP, Countdown Timer göstergeleri.
- Main Menu, Game Panel, Game Over Panel.
- Next Wave Button (skip).


 Kullanılan Oyun Motoru

- Unity 6000.0.32f1 
- Render Pipeline: URP 
- Dil: C#

Tamamlanan Görevler

- 3D ortamda 2D sprite kullanımı  
- Oyuncu hareket & saldırı (melee + ranged)  
- Wave tabanlı düşman sistemi  
- Path takibi
- UI: Gold, HP, Countdown, Menüler  
- Pause/Resume & Skip Wave  
- Game Over paneli  
- Boss wave desteği  
- ShaderGraph ,particle effect
- ObjectPool, Singleton, StressMonitor, ScriptableObject, Action, IEnumerator
 

Eklenebilir Görevler 

- Restart mekanizması
- Heal sistemi
- Shop ve level up sistemi
- Ekstra Skill ve item



Samed Bekmez

