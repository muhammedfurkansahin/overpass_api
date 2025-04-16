# overpass_api

⸻

Overpass Places API (x86_64)

Türkçe Açıklama

📌 Overpass API Nedir?

Overpass API, OpenStreetMap (OSM) veritabanına özel sorgular yaparak belirli coğrafi verileri elde etmeye yarayan, yalnızca okuma işlemi gerçekleştiren bir API’dir. Kullanıcılar, Overpass QL veya XML dillerini kullanarak belirli konumlar, nesne türleri, etiket özellikleri ve yakınlık gibi kriterlere göre veri sorgulayabilirler. Bu API, özellikle belirli bölgelerden veya belirli özelliklere sahip verileri çekmek isteyen geliştiriciler ve araştırmacılar için idealdir.  ￼ ￼

🚀 Proje Hakkında

Bu proje, Overpass API’nin özelleştirilmiş Docker imajlarını sunar. Farklı veri kapsamları ve güncelleme stratejileriyle yapılandırılmış bu imajlar, Türkiye geneli veya Konya özelinde OSM verilerini içerir. Ayrıca, düzenli olarak güncellenen bir versiyon da mevcuttur.

🧩 Özellikler
	•	Türkiye geneli veya Konya özelinde OSM verileri
	•	Güncellenmeyen veya düzenli olarak güncellenen veri seçenekleri
	•	x86_64 mimarisi için optimize edilmiş Docker imajları
	•	Kolay kurulum ve kullanım

📦 Docker İmajları

Aşağıdaki komutlarla ilgili Docker imajlarını çekebilirsiniz:
	•	Türkiye Geneli (Güncellenmeyen):

  docker pull ghcr.io/muhammedfurkansahin/overpass-places-api-x86-64:v1.0-t-db

	•	Konya Özel (Güncellenmeyen):

  docker pull ghcr.io/muhammedfurkansahin/overpass-places-api-x86-64:v1.0-n-u

	•	Düzenli Güncellenen Versiyon:

  docker pull ghcr.io/muhammedfurkansahin/overpass-places-api-x86-64:v1.0-w-u

⚙️ Kullanım

Docker konteynerini aşağıdaki şekilde çalıştırabilirsiniz:

docker run -d -p 80:80 ghcr.io/muhammedfurkansahin/overpass-places-api-x86-64:<versiyon_ismi>

<versiyon_ismi> kısmına kullanmak istediğiniz versiyonu giriniz (örneğin, v1.0-t-db).

📄 Lisans

Bu proje, Overpass API topluluğunun açık kaynak katkıları üzerine inşa edilmiştir. ￼

⸻

English Description

📌 What is Overpass API?

Overpass API is a read-only API that allows users to query specific parts of the OpenStreetMap (OSM) database based on various criteria such as location, object type, tag properties, and proximity. It is particularly useful for developers and researchers who need to extract specific geospatial data from OSM.  ￼

🚀 About the Project

This project provides customized Docker images of the Overpass API. These images are configured with different data scopes and update strategies, including versions for the entire Turkey, the city of Konya, and a regularly updated version.

🧩 Features
	•	OSM data for Turkey or Konya
	•	Options for static or regularly updated data
	•	Docker images optimized for x86_64 architecture
	•	Easy setup and usage

📦 Docker Images

Pull the desired Docker image using the following commands:
	•	Turkey-Wide (Static):

  docker pull ghcr.io/muhammedfurkansahin/overpass-places-api-x86-64:v1.0-t-db

	•	Konya-Specific (Static):

  docker pull ghcr.io/muhammedfurkansahin/overpass-places-api-x86-64:v1.0-n-u

	•	Regularly Updated Version:

  docker pull ghcr.io/muhammedfurkansahin/overpass-places-api-x86-64:v1.0-w-u

⚙️ Usage

Run the Docker container with the following command:

docker run -d -p 80:80 ghcr.io/muhammedfurkansahin/overpass-places-api-x86-64:<version_name>

Replace <version_name> with the desired version (e.g., v1.0-t-db).

📄 License

This project is built upon the open-source contributions of the Overpass API community. ￼

⸻

```
 __  __     _____           _                 ____        _     _       
|  \/  |   |  ___|   _ _ __| | ____ _ _ __   / ___|  __ _| |__ (_)_ __  
| |\/| |   | |_ | | | | '__| |/ / _` | '_ \  \___ \ / _` | '_ \| | '_ \ 
| |  | |_  |  _|| |_| | |  |   < (_| | | | |  ___) | (_| | | | | | | | |
|_|  |_(_) |_|   \__,_|_|  |_|\_\__,_|_| |_| |____/ \__,_|_| |_|_|_| |_|
                                                )__)                    
```
