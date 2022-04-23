# MR ROBOT
İndirme Bağlantısı>https://www.vulnhub.com/entry/mr-robot-1,151/

Mr Robot Çözümü için iki siteden yararlandım. Karşılaştığım problemler ve çözümleri için aldığım notları bu yazının altına bırakacağım.

https://okankurtulus.com.tr/2018/09/23/mr-robot-walkthrough-zafiyetli-makine-cozumu/

https://hguler07.home.blog/2019/02/16/mr-robot1/

Çözüme başlamadan önce kali linux ve vm yani mr robot makinelerinin ağ ayarlarını değiştirmem gerekti. VirtualBox da ilgili makine seçilip ayarlar> ağ > ağ bağdaştırıcısının "Yalnızca Anamakine Bağdaştırıcısı" seçeneğinde olması gerekiyor. Kali ve vm için bu ayarları güncellediğimizde makineleri başlatabiliriz. İşlemler kali üzerinde yapılıyor, vm de arkada çalışır şekilde oluyor.

+Çözüm sırasında kullanılan Burp Suite, kali makinenizde kurulu değilse linkini bıraktığım videoyu izleyerek hızlıca kurabilirsiniz.
https://youtu.be/Uzy28osev5g

Bu adımda firefox internete bağlanmıyorsa başta değiştirdiğimiz ağ bağdaştırıcısı seçeneğini NAT yaparak denemelisiniz. İnternet gereken durumlarda bu ayarı yapıp diğer kısımlarda baştaki duruma (Yalnızca Anamakine Bağdaştırıcısı) getirmeyi unutmayın. 

![1](https://user-images.githubusercontent.com/61375345/164943820-0ae7853e-c04a-4ac1-b81f-7e92af2850e6.png)
![2](https://user-images.githubusercontent.com/61375345/164943845-e2a2b2fb-1fb0-439b-8eb3-1f2bbe7f50ad.png)
![3](https://user-images.githubusercontent.com/61375345/164943918-a73755b6-0283-4848-9539-254806ce5687.png)
![4](https://user-images.githubusercontent.com/61375345/164944060-5ad32495-557d-4e0c-aa2a-d9ee03088840.png)
![5](https://user-images.githubusercontent.com/61375345/164944274-e7602a0b-e751-42d3-b550-bb43485a2956.png)
![7](https://user-images.githubusercontent.com/61375345/164944339-3b922fcb-6bbb-48f4-bf95-8191dba2a229.png)
![8,3](https://user-images.githubusercontent.com/61375345/164944345-1216cddd-edd0-4803-bcb3-2e7b5e504349.png)
![8](https://user-images.githubusercontent.com/61375345/164944352-ff9ab85b-5353-480a-8cd1-8ca5405f7bec.png)
![9](https://user-images.githubusercontent.com/61375345/164944370-6c150d34-8d4e-44c6-a9ae-d56f1e6b3089.png)
![10](https://user-images.githubusercontent.com/61375345/164944412-80eac5f6-dc02-4354-b302-0fc6803a4cc0.png)
![11](https://user-images.githubusercontent.com/61375345/164944417-ec0c9013-9bea-42dd-afae-702dc203650b.png)
save file seçeneği ile kaydediyoruz
![17](https://user-images.githubusercontent.com/61375345/164944436-c77a54cf-c83a-4bf8-bea1-0aec9d4be95e.png)
![18](https://user-images.githubusercontent.com/61375345/164944439-b07c23c4-a075-4e6a-86d0-7181c822c18e.png)
![20,1](https://user-images.githubusercontent.com/61375345/164944453-ee5fb5cc-5d19-406f-9778-567e01b4b1df.png)
![20](https://user-images.githubusercontent.com/61375345/164944463-998f7167-82ac-4d33-914f-0efc3945fe22.png)
![21 başka root penceresinde](https://user-images.githubusercontent.com/61375345/164944469-36148496-1e4f-443c-9ddd-4e7d6a785452.png)
![21 devam](https://user-images.githubusercontent.com/61375345/164944475-dc077a5f-3641-4ad9-82c8-35eb6cce6d9d.png)
![21 sonuç](https://user-images.githubusercontent.com/61375345/164944506-6259aa6a-b21d-421c-b0be-783057947c6f.png)
![21 vee ikinci anahtar](https://user-images.githubusercontent.com/61375345/164944510-2e060303-3574-4c27-955e-c4d17ddf4f0a.png)
![21](https://user-images.githubusercontent.com/61375345/164944516-0b8662b7-06af-4480-8087-887c254dc132.png)
![22](https://user-images.githubusercontent.com/61375345/164944535-3915c367-0b9a-4332-9fbe-ece3a5081216.png)
![23 ve son anahtar](https://user-images.githubusercontent.com/61375345/164944558-3572a49a-f089-4ea2-9b9e-a69632d7892f.png)


