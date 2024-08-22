[TR]

### Görev Kapsülleme:

“Password” adında, “password” ve “username” adlı niteliklere sahip kapsüllenmiş bir sınıf oluşturun. Getters ve setters ile birlikte aşağıdaki koşulları ekleyin:

* `username` yalnızca `null` ise set edilsin.
* `username` yalnızca ilk üç karakteri doğru ise get ile alınabilir.
* `password` yalnızca `null` değilse ve `username` doğru sağlanmışsa set edilebilir.
* `password` yalnızca `username` doğru ise get edilebilir.

---

[EN]

### Task Encapsulation:

Create a class named “Password” with encapsulated attributes “password” and “username”. Along with getters and setters, add the following conditions:

* `username` can only be set if it is currently `null`.
* `username` can only be retrieved (get) if the first three characters are correct.
* `password` can only be set if it is not `null` and `username` is correctly provided.
* `password` can only be retrieved (get) if `username` is correct.
