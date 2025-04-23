# sqlite-code-kurulum-
Data klasörü aç normal
içine ad sonra Context mesala KitapContext

ef-dbcontext

diyerek gerekli şeyler


dotnet add package Microsoft.EntityFrameworkCore

dotnet add package Microsoft.EntityFrameworkCore.Sqlite

dotnet add package Microsoft.EntityFrameworkCore.Design



bunları kurduktan sonra 1 kaç hata düzelir bide



 optionsBuilder.UseSqlite("Data Source=Kitapdb.db");
 
 usesqlite için olarak değiştir (içeri Data  Source= yer db.db);

  public DbSet<Kitap> Kitaplar { get; set; }

  
  list oluşyutma veri tablosu yeri

  
  builder.Services.AddSingleton<KutuphaneContext>();

  
  bu nda KutuphaneContext data içindeki yer  data içinde veri yeri list 
  genel global yapar
var olup olmaması 


dotnet ef 

dotnet tool install dotnet-ef --globall


kurmak için 
ondan sonra yer oluşturmak için 


dotnet ef migrations add a1


yüklemek için 


dotnet ef database update

