**お問い合わせフォーム**

*環境構築*

Dockerビルド

　1.git clone リンク

　2.docker-compose up -d build

Laravel環境構築
　
　1.docker-compose exec php bash
  
　2.composer install
  
　3..env.exampleファイルから.envを作成し、環境変数を変更

　4.php artisan key:generate

　5.php artisan migrate

　6.phpartisan db:seed

*使用技術*

　・php 8.0
  
　・Laravel 10.0
  
　・MySQL　8.0

 ER図

 
![スクリーンショット 2024-11-24 200844](https://github.com/user-attachments/assets/c95881d3-6862-468c-b5a9-af746950d076)

　・開発環境：http://localhost/

　・phpMyAdmin:http://localhost:8080/
