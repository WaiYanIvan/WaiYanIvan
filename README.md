- 👋 Hi, I’m @WaiYanIvan
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
WaiYanIvan/WaiYanIvan is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
// Product.java
public class Product {
    private int id;
    private String name;
    private double price;
    // Constructors, getters, setters
}

// User.java
public class User {
    private int id;
    private String username;
    private String password;
    // Constructors, getters, setters
}

// Order.java
public class Order {
    private int id;
    private User user;
    private List<Product> products;
    // Constructors, getters, setters
}

// ProductController.java
@RestController
@RequestMapping("/products")
public class ProductController {
    // Implement methods for listing, searching, and displaying products
}

// OrderController.java
@RestController
@RequestMapping("/orders")
public class OrderController {
    // Implement methods for handling orders and checkout
}

