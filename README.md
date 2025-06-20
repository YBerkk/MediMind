# MediMind
Türkçe doğal dil işleme ile çalışan ön tanı destek sistemi – TEKNOFEST 2025 Projesi
******  
TEKNOFEST 2025 – Türkçe Doğal Dil İşleme Yarışması (Serbest Kategori) Projesi

## Proje Tanımı  
MediMind, kullanıcıların serbest şekilde yazdığı Türkçe semptom cümlelerinden yola çıkarak olası hastalıkları tahmin eden bir ön tanı asistanıdır.  
Sistem, doğal dil işleme (NLP) teknikleriyle semptomu anlamlandıracak, bağlamsal yorumlama yapacak ve tahmin edilen hastalıkla ilgili açıklayıcı bilgiler sunacaktır. Kullanıcıdan gelen bilgi yetersizse ek sorular sorarak etkileşimli şekilde süreci yönetecektir.

## Kullanılan Yöntemler  
- Türkçe semptom-hastalık eşleşmelerinden oluşan özel veri seti (manuel toplanmış)  
- `dbmdz/bert-base-turkish-cased` modeline dayalı BERT transfer öğrenmesi  
- Flask ile geliştirilen web API  
- HTML/CSS/JS ile arayüz prototipi  
- Değerlendirme metrikleri: Accuracy, Precision, Recall, F1 Score

## Proje Durumu  
Proje şu anda geliştirme aşamasındadır. Veri toplama, ön işleme ve model eğitimi süreciyle eş zamanlı olarak arayüz geliştirme çalışmaları yürütülmektedir.  
Projeye ait kodlar, veri dosyaları ve arayüz bileşenleri, geliştirme süreci boyunca uygun klasör yapısında bu repoya eklenecektir.

## Hedefler  
- Türkçe NLP tabanlı bir sağlık destek sistemi oluşturmak  
- Elle toplanan örneklerle yüksek doğrulukta çalışan bir sınıflandırma modeli üretmek  
- Statik sistem yerine kullanıcıyla etkileşim kurabilen bir agent yapısı tasarlamak  
- Açık kaynak olarak paylaşılabilir, sosyal fayda sağlayacak bir temel sistem geliştirmek

-- Proje henüz geliştirme aşamasındadır. İlerleme güncellemeleri bu repo üzerinden paylaşılacaktır.
#BilisimVadisi2025  
#TürkiyeAçıkKaynakPlatformu  
#YBK
