# BasicBankingInJava

Program,kullanıcı konsoldan müşteri numarasını girerse düzgün çalışıyor fakat şöyle bir problem var ki 
Kod kullanıcıyı algılayamıyor kodu incelerseniz kullanıcı "k100" ve "k101" için ayrı ayrı işlem kodları tekrarlandı
İki kullanıcı varken problem değil ama 100 kullanıcı olsaydı problem olacaktı
Benim yapamadığım şey programın müşteri numarasını aldığı anda artık işlemleri o müşteri numarası üzerinden yapması ve kodların
tekrarlanmak zorunda kalınmaması.

Örneğin:
System.out.println("Geben Sie Ihre Kundennummer ein.");
        String Benutzer = scan.nextLine();
        if ("k100".equals(Benutzer)) {
            System.out.println("Willkommen Ihre Konto " + k100.KundenName);//Tam olarak burada k100.KundenName yazmak yerine
                                                                              Benutzer.KundenName yazabilsem tüm problemim çözülecek
                                                                              ama denedim çalışmıyor.İlla k100. olarak kendim belirtmem 
                                                                              gerekiyor müşteri numarasını.
            
            
            
