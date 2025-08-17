# IMDB Movie Review Analysis
### Overview
Dataset IMDB movie Review ini berisi 2 label yaitu sentiment dan review. Sentiment adalah label yang berisi sentiment positif atau negatif, sedangkan review adalah label yang berisi review dari user imdb terhadap film tertentu. Hal yang ingin dianalisis dari dataset ini adalah indikator apa saja yang menjadi bahan review suatu film misalnya entah dari sisi dialog, plot, akting, dsb, bagaimana aspek film yang disukai dan tidak disukai oleh reviewer, dan film apa saja yang terindikasi berkualitas dari review.

---

### Raw Dataset Link
Link 1 : https://www.kaggle.com/api/v1/datasets/download/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
Link 2 :https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

---

### Insight & Findings
Dari analisis yang dilakukan berdasarkan 50 data. Dapat diketahui bahwa umunya para reviewer di IMDB biasa membuat sentimen atau review terhadap film yang mereka tonton berdasarkan :
1. penilaian terhadap alur cerita, orisinalitas, dan perkembangan plot. Narasi yang menarik sering dipuji, sementara plot yang berbelit-belit atau mudah ditebak dikritik. 
2. Kualitas akting, kredibilitas, dan kedalaman penggambaran karakter yang ada pada film.
3. Aspek Teknis yang mencakup sinematografi, penyuntingan, desain suara, efek khusus, dan desain set.
4. Bagaimana sebuah film dapat mengeksplorasi tema, menyampaikan komentar sosial, dan menyampaikan pesan yang dimaksudkan.
5. Kemampuan sebuah film untuk membangkitkan emosi, entah itu tawa, air mata, ketegangan, atau perasaan lainnya.
6. Kenyamanan dan keterlibatan murni yang diberikan sebuah film, terlepas dari nilai artistiknya, merupakan pertimbangan utama kebanyakan reviewer.
7. Kesesuaian terhadap atau subversi ekspektasi genre, khususnya dalam horor, aksi, romansa, dll.
8. Sesuatu yang baru atau mengubah kiasan yang sudah ada dari suatu film sebelumnya.
9. Kesesuaian terhadap kejadian nyata atau periode sejarah untuk film yang dibuat berdasarkan kisah nyata atau sejarah.
10. Fase dan struktur film.
11. Storytelling, teknis kamera, dan editing suatu film.

Selain itu, dari dataset ini juga bisa diketahui bahwa ada beberapa aspek film yang bisa memengaruhi kenyamanan audiens. Diantaranya adalah 
1. Realisme dan dan penceritaan dimana film yang menyajikan pandangan apa adanya dan tanpa filter terhadap isu atau latar dunia nyata, seperti "Oz" yang menggambarkan kehidupan penjara, dan "Cold Mountain" yang menggambarkan wilayah Selatan pada era Perang Saudara, dsb.
2. Akting yang unik, berkualitas, dan terarah. Contohnya termasuk "A Wonderful Little Production" karena realisme dan penampilan luar biasa, dan "The Cell" karena visualnya yang memukau dan arahan Tarsem Singh.
3. Alur cerita yang unik dan menarik, seperti terlihat dalam "The Rage" (meskipun ada kekurangannya) dan "Cold Mountain," dinikmati karena kedalaman dan orisinalitasnya.
4. Musik atau soundtrack yang digunakan dalam film. seperti soundtrack dalam "Love in the Time of Money," diapresiasi karena meningkatkan pengalaman keseluruhan.
5. Film yang karakternya berhasil dibentuk dari berbagai perspektif seperti emosi yang kompleks dan latar belakangnya.
6.  reviewer menghargai film karena humor dan faktor hiburannya yang unik, terlepas dari kekurangan teknisnya.
7. Film yang mengangkat tema sejarah dan budaya tanpa mengurangi nilai otentiknya.
8. Film dengan sinematografi, desain set, dan efek khusus yang mengesankan
---

### Ai Support Explanation
Dalam Proses Analisis AI model IBM granite-3.3-8b-instruct digunakan dalam mencari insight dan findings dari label Sentimen, label review yang berisi positif dan negatif itu sendiri digunakan untuk memilah bagaimana aspek dan indikator film yang baik lewat analisis sentimen yang dibantu oleh model.
