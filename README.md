
![Logo](https://enrichmobile.app/images/logo-footer.png)
# About Us
Enrich mobile was founded in the beginning of 2020 with the aim of creating amazing & useful apps for the global mobile app community. Enrich Mobile has two core values that the company is based on; end to end app development and publishing. Since the start of 2021, the firm is now also focused on investing in promising app projects and startups. With a solid in house development and design team and a solid background in mobile app development, Enrich Mobile is bound to become the next big hit in the global mobile arena.

🔗 Links

[![website](https://img.shields.io/badge/Web_Site-000?style=for-the-badge&logoColor=white)](https://enrichmobile.app//)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/enrichmobile)

# iOS Assignment

The purpose of this assignment is creating an iOS app that will fetch the current pre-design instagram templates and display the templates in a clear User Interface.

We are expecting you to implement a listing page and a detail page for the cars' adverts. On the listing page, you need to use the "listing" endpoint and show the advert list to the user. And, also you need to show a single-vehicle detail with the "detail" endpoint. You can find more information about endpoints in the Sandbox API section.

Sizden listeleme sayfası ve listelenen içeriğin basit detay sayfası ile birlikte abonelik ekranından oluşan üç adet ekran tasarlamanızı bekliyoruz. Aşağıdaki üç ekran için de istenilenler ile birlikte örnek ekran görüntülerini bulabilirsiniz. 

 Listeme Sayfası
* Belirtilen endpoint’te bulunan “section” adlarına göre sayfanın üstünde menünün entegrasyonu
* Her bir menüye tıklandığında, o menüye ait template’lerin sayfada aşağıdaki örnek screenshot gibi listelenmesi
* Template seçildiğinde, detay sayfasına yönlendirilmesi

Detay Sayfası
* Seçilen template’in fotoğrafının ekranda gösterilmesi
* Eğer “isFree” false ise abonelik ekranına gönderen butonun alt kısımda belirmesi, true ise butonun gösterilmemesi.

Abonelik Sayfası
* Aşağıdaki ekran görüntüsüne göre tasarımın oluşturulması
* Çarpı butonu en son kaldığı sayfaya geri dönmeli


## API Reference

#### Get all templates

``http
  GET - storly-dev.herokuapp.com/storly/api/templates
``

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `templateCoverImageUrlString` | `string` | image url |
| `section` | `string` |  categories |
| `isFree` | `boolean` |  paid or not status |




## Screenshots
 <b> Home Screen </b>
 
![App Screenshot](https://media.giphy.com/media/TzJ5b2QiQ32yZdSVqO/giphy.gif)


 <b> Subscription Screen </b>
<p align="left">
<img src="https://www.linkpicture.com/q/IMG_0137.jpg" width ="300" height="600"/>
</p>



## Feedback

If you have questions, you can ask to us when you want or need to help. If there is a problem, please don't hesitate about contact to fatih@enrichmobile.app
