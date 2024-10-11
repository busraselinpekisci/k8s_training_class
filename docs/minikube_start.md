#Minikube Start

Minikube'u başlatmak için aşağıdaki adımları izleyebilirsiniz:

1. **Minikube'un Yüklü Olduğundan Emin Olun**: Minikube'un yüklü olduğundan emin olun. Terminalde aşağıdaki komutu çalıştırarak kontrol edebilirsiniz:

   ```bash
   minikube version
   ```

2. **Minikube'u Başlatın**: Aşağıdaki komutla Minikube'u başlatın:

   ```bash
   minikube start
   ```

![](./images/minikube_start_result.jpg)

   Bu komut, varsayılan bir Kubernetes kümesi oluşturacak ve çalıştıracaktır.

3. **Durumu Kontrol Edin**: Minikube'un başarılı bir şekilde başlatıldığını kontrol etmek için şu komutu kullanabilirsiniz:

   ```bash
   minikube status
   ```

![](./images/minikube_status_result.jpg)

4. **Kubernetes Dashboard'a Erişim**: Minikube başlatıldıktan sonra, Kubernetes Dashboard'u açmak için şu komutu kullanabilirsiniz:

   ```bash
   minikube dashboard
   ```

Bu adımlar, Minikube'u başlatmak için gereken temel işlemleri kapsar. Eğer belirli bir sürüm veya ayar gerekiyorsa, komutları buna göre özelleştirebilirsiniz.