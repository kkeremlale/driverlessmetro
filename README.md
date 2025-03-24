# driverlessmetro
Akbank Python ve Yapay Zekaya Giriş
# **Driverless Metro Simulation**  

Bu proje, **otonom bir metro sisteminde en hızlı ve en az aktarmalı rotaları bulmak** için tasarlanmıştır.  
Kullanıcılar, **BFS (Breadth-First Search)** ve **A* (A-Star)** algoritmalarını kullanarak iki istasyon arasındaki **en iyi rotayı** belirleyebilirler.  

## **Kullanılan Kütüphaneler ve Açıklamaları**  

### **1. collections**  
Python’un `collections` modülü, gelişmiş veri yapıları sağlar. Bu projede şu bileşenler kullanılmıştır:  

- **`defaultdict`** → Varsayılan bir değer atayarak sözlükleri yönetir.  
  - **Kullanım:** **Metro hatlarını ve istasyon bağlantılarını saklamak için**  
- **`deque`** → Çift uçlu kuyruk yapısı sağlar ve BFS için idealdir.  
  - **Kullanım:** **BFS algoritmasında kuyruk veri yapısı olarak kullanılmıştır.**  

---

### **2. heapq**  
Python'un **öncelik kuyruğu** (priority queue) yapısını sağlar.  
- **Kullanım:** **A* algoritmasında en hızlı rotayı hesaplamak için**  

---

### **3. typing**  
Kodun okunabilirliğini artırmak için **veri türlerini belirtir**.  

**Kullanılan Algoritmalar**
1. BFS (Breadth-First Search) - En Az Aktarmalı Rota
BFS, en kısa adımlı geçişleri hesaplamak için kullanılan bir algoritmadır.
Bu projede en az aktarmalı metro rotasını bulmak için kullanılmıştır.

2. A* Algoritması - En Hızlı Rota
A* , en kısa süreyi bulmak için kullanılan bir arama algoritmasıdır.
Bu projede en hızlı metro rotasını bulmak için kullanılmıştır.
