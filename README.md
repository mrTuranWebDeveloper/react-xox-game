# react-xox-game

# X-Oyunu (Tic-Tac-Toe) Uygulaması

Bu proje, React kullanılarak geliştirilmiş bir X-Oyunu (Tic-Tac-Toe) uygulamasını içermektedir. Oyun tahtasını oluşturur, oyuncuların kareleri tıklamasını ve oyunun akışını yönetir. Aynı zamanda oyunun geçmiş hamlelerini takip eder.

## Nasıl Çalıştırılır?

1. Bu projenin kopyasını bilgisayarınıza indirin veya klonlayın.
2. Proje klasörüne gidin ve terminali açın.
3. Gerekli bağımlılıkları yüklemek için aşağıdaki komutu çalıştırın:

   ```bash
   npm install

Proje bağımlılıkları yüklendikten sonra, aşağıdaki komutu kullanarak uygulamayı başlatın:

bash
Copy code
npm start
Tarayıcınızda http://localhost:3000 adresine gidin. Uygulama başarılı bir şekilde yüklendiyse X-Oyunu oynamaya başlayabilirsiniz!

Oyun Nasıl Oynanır?
Oyun iki oyuncu arasında oynanır. Bir oyuncu X sembolünü temsil ederken diğer oyuncu O sembolünü temsil eder.
Sıra ile her oyuncu, boş bir kareye sembolünü yerleştirir. Oyun tahtası 3x3 kareden oluşur.
Oyuncular, sırayla kareler üzerine tıklayarak sembollerini yerleştirirler.
Oyunun amacı, üç sembolü yatay, dikey veya çapraz olarak birleştirmektir.
Eğer bir oyuncu bu şartı sağlarsa, oyunu kazanır.
Eğer tüm kareler dolduğunda ve bir kazanan yoksa, oyun berabere biter.
Uygulama Yapısı
Square bileşeni: Bir kareyi temsil eder. value ve onSquareClick özelliklerini alır.
Board bileşeni: Oyun tahtasını temsil eder. xIsNext, squares ve onPlay özelliklerini alır.
Game bileşeni: Oyunun ana bileşeni. history ve currentMove state değişkenlerini kullanır. Oyunun akışını yönetir.
calculateWinner işlevi: Kazananı hesaplamak için kullanılır.
Proje, React'in temel kavramlarını ve bileşen tabanlı bir uygulama yapısını anlamak için iyi bir örnektir. İyi eğlenceler!



Bu `readme.md` dosyası, projenin nasıl çalıştırılacağı, nasıl oynanacağı ve uygulama yapısı hakkında temel bilgileri içeriyor. Projenin amacını ve nasıl kullanılacağını anlatırken, bileşenlerin ve işlevlerin ne işe yaradığını da açıklıyor.
