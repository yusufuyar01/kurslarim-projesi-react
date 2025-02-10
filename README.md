# Kurslarım Projesi React

 React çalışmaları 6

 - [Proje Hakkında](#proje-hakkında)
 - [Projenin Kurulumu ve Çalıştırılması](#projenin-kurulumu-ve-çalıştırılması)


## Proje Hakkında:  
 Bu react çalışmasında yaptığım sayfada "kurslarım" başlığı altında, db.json dosyasından `json-server` aracılığıyla çektiğim dataları card yapısında gösterdim. 5 kurs var ve bu 5 kursta id, başlık, içerik ve fiyat propsları bulunmaktadır. Projede db.json dosyasından veri çekmek için `axios` kullandım. 
<br/>
<br/>
## Projenin Kurulumu ve Çalıştırılması:  <br/>
Bu projenin bağımlılıkları `npm` ve `npx` kullanarak kolayca yüklenebilmektedir.

 Projeyi çalıştırmak aşağıdaki adımları izleyiniz:
 1) Porjeyi zip olarak indirin ya da klonlayın:
 https://github.com/yusufuyar01/kurslarim-projesi-react.git
 
2) Ardından proje klasörünü açın:
   cd kurslarim-projesi-react ya da  cd tkurslarim-projesi-react-main
3) Gerekli bağımlılıkları yükleyin:<br/>
 npm install  #Bağımlılıkları indirir. <br/> 
 npm install axios  #Axios api bağlantı kurulumu yapar.<br/>
 npm install json-server  #db.json dosyasını kullanabilmek için json-serverı kurduk.<br/>
4) Yeni bir terminal açın ve 3001 portunda json-serverı çalıştırın:<br/>
 json-server --watch api/db.json --port 3001 #json-serverı çalıştırır
5)  React projesini çalıştırın:<br/>
 npm start  #Projeyi başlatır.<br/>
 
 
<br/>


