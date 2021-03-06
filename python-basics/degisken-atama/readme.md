# Değişken Atama (Variable Assignment)

- Bazı değerleri bilgisayarın hafızasında tutmak ve daha sonra bunlara verdiğimiz adlarla erişmek isteyebiliriz. Bunu variable'lar ile gerçekleştireceğiz.

  

- İlk olarak yapacağımız şey variable'a vereceğimiz ismi yazmak. Bu isim `penguen`, `uzunluk`, `maaş` gibi istediğiniz bir isim olabilir (burada dikkat edilmesi gereken yer, verilecek ismin daha önceden python'ın default olarak kullanmadığı isimler olması. Mesela `if`, `continue`, `for` gibi keyword'ler daha önceden ayrıldığı için bunları variable ismi olarak kullanamayız)

  

- Python'ın daha önceden kendisine ayırdığı isimler (**reserved words**):

  
   
  
        and       del       from      not       while    
        as        elif      global    or        with     
        assert    else      if        pass      yield    
        break     except    import    print     True         
        class     exec      in        raise     False         
        continue  finally   is        return             
        def       for       lambda    try
     



- Variable ismini seçtikten sonra bu ismin değerinin ne olacağını söylemeliyiz. Bu aşamadan sonra python verdiğimiz ismi gördüğünde aslında verdiğimiz değeri çağırıyor olacak.



- Bu değer atama işlemini `=` sembolü ile yapacağız. Normalde bildiğimiz anlamından farklı bu `=` işareti. Eşitliğin sağındaki değeri solda yazdığımızın değeri olarak ata demiş oluyoruz bununla. Bu işleme `variable assignment` deniyor.



```python
a = 2
```


```python
a
```

> 2




```python
a + 5
```

>  7




```python
b = 2 + 4
```


```python
b
```

> 6




```python
b + 4
```

> 10



* Artık kodun başka bir yerinde `a` ile işlem yapmaya çalışsam python `a`'ya `2` olarak davranacak

* Variable assingment'ı kafamızda canlandırmak için şöyle düşünebiliriz:
    * Variable'a bir isim verip bir atama yaptığımızda python bilgisayarın hafızasında o isimli bir konteyner oluşturuyor ve ismini verdiğimiz isim yapıyor. Daha sonra bu isim çağrıldığında o konteynera gidiyor ve o değeri alıyor

![](figures/variable_assignment.png)

