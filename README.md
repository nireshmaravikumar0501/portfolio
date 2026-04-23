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
<img width="3840" height="2400" alt="Acer_Wallpaper_04_3840x2400" src="https://github.com/user-attachments/assets/d677db8c-255e-45dc-b486-98cbe712c014" />

