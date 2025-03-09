# iOS/macOS Interview Important Topics

## Video Resources

| Topic | Video Link |
|-------|------------|
| Singleton Pattern | ▶️ [Understanding Singletons in Swift](https://www.youtube.com/watch?v=fiu0DmbnVn0) |
| Comprehensive Networking | ▶️ [iOS Networking Fundamentals](https://www.youtube.com/watch?v=II7WcnHVG4U&list=PLRcTS2CSnBfPY3bdp0OKMkl9hstKMyrOk&index=6) |
| Full playlist Best for ios Mac Learning | ▶️ [Full playlist Best for ios Mac Learning](https://www.youtube.com/watch?v=lkU5s5V1GTg&list=PLRcTS2CSnBfPY3bdp0OKMkl9hstKMyrOk) |
| swift programming fundamentals | ▶️ [swift programming fundamentals](https://www.youtube.com/watch?v=b5abCaytv5M&list=PLRcTS2CSnBfMbk7n5SYBQQhL6iyRf2i81) |
| Swift Retain Cycle / Memory Leak Explained | ▶️ [Swift Retain Cycle / Memory Leak Explained](https://www.youtube.com/watch?v=XAlXnApplk0) |



## Questions

What is Delegation Design pattern? > delegate protocol, delegate vs protocol




https://www.youtube.com/watch?v=O99H4BhE0Q0 

how to optimise performance of slow ios app

struct vs class in swift

how to handle concurrency in swift

ios security and encryption

ios app life cycle and dlegate methods

handling crashes and errors in ios app

concept of memory management in ios applicatiom

how to decrease battery consumption by your app

swiftui vs uikit

how to implement accessibility feature in ios app

ci/cd in ios apps

https://www.youtube.com/watch?v=vLtZ84pF-nU


why a class need to confirm to observable protocol?
Ans:
Conforming your view model (such as ApiViewModel) to the ObservableObject protocol is key for SwiftUI’s reactive data flow. Here’s why:

Automatic UI Updates: When properties marked with @Published in your view model change, the ObservableObject automatically notifies all views that are observing it. This triggers SwiftUI to re-render those views, ensuring the UI stays in sync with your data.

Reactive Data Binding: By conforming to ObservableObject, your view model becomes an observable source of truth. SwiftUI uses property wrappers like @ObservedObject or @StateObject to subscribe to changes, enabling a reactive programming model.

Cleaner Code: This approach minimizes manual state management. Instead of updating the UI explicitly when data changes, SwiftUI handles it for you based on the published changes.

In summary, adopting the ObservableObject protocol allows you to build a dynamic, responsive UI that automatically reflects changes in your view model's data.



https://nmn.gl/blog/ai-and-learning

Swift Retain Cycle / Memory Leak Explained (iOS Interview Question)
Memory Management | Retain Cycles | Weak Self


# Frameworks to explore 

combine 
relm
shold know what is in last wwdc update for ios ,mac ,swift etc
xcode new features etc


