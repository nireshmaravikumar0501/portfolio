# Portfolio

## Program

```jsx
import { AnimatePresence, motion } from "framer-motion";
import { Route, useLocation } from "react-router-dom";

function App() {
 const location = useLocation();

 return (
   <motion.div>
      <Route path="/" element={<HomePage />} />
      <Route path="/contact" element={<ContactPage />} />
   </motion.div>
 );
}

export default App;
```

## Output

![Portfolio Screenshot](https://github.com/user-attachments/assets/your-image-link)
