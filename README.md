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

![drawio](https://github.com/user-attachments/assets/54fd8f80-c470-4fbd-a653-95a3c1c97f2a) 

　・開発環境：http://localhost/

　・phpMyAdmin:http://localhost:8080/
