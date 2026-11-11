> 🇬🇧 English below · 🇹🇷 [Türkçe açıklama](#üniversite-öğrencileri-için-akademik-iş-birliği-platformu-mvp)

# Academic Collaboration Platform for University Students (MVP)

**Status: prototype, in development.** This is a front-end MVP with demo data. There is no backend yet, and the name and visual design are not final.

A platform where university students follow content from their own field, ask questions, find teammates for projects and keep track of deadlines. An application to develop it as a research project was submitted to the TÜBİTAK 2209-A undergraduate research programme (2026 call).

## Why

Students hear about competitions, hackathons and research opportunities late or not at all, and finding a suitable teammate outside one's own class is hard. The platform puts course-related content, opportunities and team matching in one place, open only to verified students.

## What the MVP shows

| Section | What it does |
|---|---|
| Sign-up | Registration with a `.edu.tr` student e-mail, so every account belongs to a student; department, year and interests are collected for matching |
| Akış (Feed) | Posts, articles, videos and podcasts related to the student's department, each with a short summary; upcoming application deadlines |
| Atölye (Workshop) | Three post types: questions (the asker can mark an answer as the solution), open discussions, and achievements |
| Proje Panosu (Project Board) | Team adverts written like job postings: who can apply, required conditions, weekly workload, application questions. Students cannot apply to adverts whose conditions they do not meet, and applicants are ranked by how well they match |
| Ekiplerim (My Teams) | Messaging, opened only inside teams that have been formed |
| Takvim (Calendar) | Course goals and opportunity deadlines; items can be dragged onto a day |
| Gelişim (Progress) | The student's own progress on the platform |

## Research design

The platform is the intervention in a planned 12-month study, run by a team of three undergraduate students from different departments.

**Research question.** How do a personalised academic content feed and skill-based team matching affect undergraduate students' awareness of academic opportunities, their application rate to those opportunities, and the time it takes them to form a project team?

**Design.** A pre-test / post-test experiment with a waiting-list control group. Participants are randomly assigned to two groups; the first gets access in month 5 and the second in month 8, so the second group acts as the control in the first phase and no participant is left without access. A power analysis (d = 0.50, alpha 5%, power 80%) calls for at least 120 participants.

**Hypotheses.** Compared with the waiting-list group, the group with access will show (H1) a larger increase in opportunity-awareness score, (H2) a higher application rate, and (H3) a shorter time to form a team.

**Data and analysis.** An opportunity-awareness scale developed for the study (target Cronbach's alpha of 0.70 or above), platform usage data (interactions, advert views, team-formation timestamps) and semi-structured interviews. Awareness scores are analysed with mixed-design ANOVA (group x time), with non-parametric tests where normality does not hold; effect sizes are reported.

## How to run

Open `index.html` in a browser. The whole MVP is a single HTML file with no build step. The login form is pre-filled with demo values; all names and content inside are sample data. The interface is in Turkish.

## Planned next

- Backend and real data exchange (Supabase, EU region) with hosting on Vercel
- Compliance with KVKK, the Turkish data-protection law
- A student survey to measure the need for the platform

## Author

Hilal Elçin Şahin · BSc Data Science and Analytics, Mehmet Akif Ersoy University

---

# Üniversite Öğrencileri için Akademik İş Birliği Platformu (MVP)

**Durum: prototip, geliştirme aşamasında.** Bu, demo verilerle çalışan bir ön yüz MVP'sidir. Henüz arka uç yoktur; ad ve görsel tasarım kesinleşmemiştir.

Üniversite öğrencilerinin kendi alanlarıyla ilgili içerikleri takip ettiği, soru sorduğu, projeleri için ekip arkadaşı bulduğu ve son başvuru tarihlerini izlediği bir platform. Platformu bir araştırma projesi olarak geliştirmek üzere TÜBİTAK 2209-A Üniversite Öğrencileri Araştırma Projeleri Destekleme Programı'na (2026 çağrısı) başvuru yapılmıştır.

## Neden

Öğrenciler yarışma, hackathon ve araştırma fırsatlarından geç haberdar oluyor ya da hiç haberdar olmuyor; kendi sınıfı dışından uygun ekip arkadaşı bulmak da zor. Platform, dersle ilgili içerikleri, fırsatları ve ekip eşleştirmeyi yalnızca doğrulanmış öğrencilere açık tek bir yerde toplar.

## MVP'de neler var

| Bölüm | Ne yapar |
|---|---|
| Kayıt | `.edu.tr` uzantılı öğrenci e-postasıyla kayıt; böylece her hesap bir öğrenciye aittir. Eşleştirme için bölüm, sınıf ve ilgi alanları alınır |
| Akış | Öğrencinin bölümüyle ilgili gönderiler, makaleler, videolar ve podcast'ler; her içeriğin altında kısa özet. Son başvuru tarihi yaklaşan fırsatlar |
| Atölye | Üç paylaşım türü: soru (soran kişi bir cevabı çözüm olarak işaretleyebilir), fikir alışverişi ve başarı paylaşımı |
| Proje Panosu | İş ilanı gibi hazırlanan ekip ilanları: kimler başvurabilir, zorunlu şartlar, haftalık süre, başvuru soruları. Öğrenci şartlarını karşılamadığı ilana başvuramaz; başvurular şartlarla örtüşme derecesine göre sıralanır |
| Ekiplerim | Yalnızca kurulmuş ekiplerin içinde açılan mesajlaşma |
| Takvim | Kurs hedefleri ve fırsatların son başvuru tarihleri; etkinlikler bir güne sürüklenebilir |
| Gelişim | Öğrencinin platformdaki kendi ilerlemesi |

## Araştırma tasarımı

Platform, farklı bölümlerden üç lisans öğrencisinin yürüteceği 12 aylık bir araştırmanın müdahalesidir.

**Araştırma sorusu.** İlgi profiline göre kişiselleştirilmiş akademik içerik akışı ve beceri temelli ekip eşleştirmesi; lisans öğrencilerinin akademik fırsatlardan haberdar olma düzeyini, bu fırsatlara başvuru oranını ve proje ekibi kurma süresini nasıl etkilemektedir?

**Desen.** Bekleme listesi kontrol grubu içeren ön test – son test deneysel desen. Katılımcılar iki gruba yansız atanır; birinci grup 5. aydan, ikinci grup 8. aydan itibaren platforma erişir. Böylece ikinci grup ilk fazda kontrol grubu olur ve hiçbir katılımcı erişimden yoksun kalmaz. Güç analizi (d = 0,50, %5 yanılma düzeyi, %80 güç) en az 120 katılımcı gerektirmektedir.

**Hipotezler.** Platforma erişimi olan grupta, bekleme listesindeki gruba göre (H1) fırsat farkındalığı puanındaki artış daha yüksek, (H2) başvuru oranı daha yüksek, (H3) ekip kurma süresi daha kısadır.

**Veri ve analiz.** Çalışma için geliştirilecek fırsat farkındalığı ölçeği (hedef: Cronbach alfa 0,70 ve üzeri), platform kullanım verisi (etkileşim, ilan görüntüleme, ekip kurma zaman damgaları) ve yarı yapılandırılmış görüşmeler. Farkındalık puanları karma desenli varyans analiziyle (grup × zaman), normallik sağlanmadığında parametrik olmayan testlerle çözümlenir; etki büyüklükleri raporlanır.

## Çalıştırma

`index.html` dosyasını tarayıcıda açın. MVP'nin tamamı tek bir HTML dosyasıdır, derleme adımı yoktur. Giriş formu demo değerlerle dolu gelir; içerideki bütün adlar ve içerikler örnek veridir.

## Sıradaki adımlar

- Arka uç ve gerçek veri alışverişi (Supabase, AB bölgesi), Vercel üzerinde barındırma
- KVKK'ya uyum
- Platforma duyulan ihtiyacı ölçmek için öğrenci anketi

## Hazırlayan

Hilal Elçin Şahin · Veri Bilimi ve Analitiği, Burdur Mehmet Akif Ersoy Üniversitesi
