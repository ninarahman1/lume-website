graph TD
    A[Start: Login to Lumé] --> B[Browse Categories / Search Products]
    B --> C{Interested?}
    C -- No --> B
    C -- Yes --> D[Add Product to Cart]
    
    D --> E{Continue Shopping?}
    E -- Yes --> B
    E -- No --> F[View Shopping Bag]
    
    F --> G[Proceed to Checkout]
    
    G --> H[Enter UMSKAL Block & Room Info]
    H --> I[Review Order & Total RM]
    
    I --> J[Confirm Order - Cash on Delivery]
    
    J --> K[Order Placed Successfully]
    K --> L[Track Order Status in Dashboard]
    
    L --> M{Status: Out for Delivery?}
    M -- No --> L
    M -- Yes --> N[Receive WhatsApp Alert from Seller]
    
    N --> O[Meet Seller at Block Lobby]
    O --> P[Pay Cash & Receive Items]
    P --> Q[End: Order Completed]
