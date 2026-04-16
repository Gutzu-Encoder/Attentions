# Attentions
repo นี้มีไว้เพื่อเป็นการทบทวนเรื่อง Attention ส่วนตัวของผู้เขียนซึ่งไม่ได้หมายถึงเเค่ scale-dot product attention เเต่จะพูดถึง
- self-attention
- Cross-attention
รวมถึง variation ต่างๆของการประยุกต์ใช้ attention เช่น
- KV cache ที่มีไว้เพื่อช่วยลด memory จากการคำนวณซ้ำซ้อนที่ไม่จำเป็น
- Group Query Attention ที่หลายๆโมเดลอย่าง gemma llama qwen ใช้ ซึ่างจะนำ KV cache มาใช้
(** ไม่ได้พูดถึง Multi-Query Attention เพราะคล้าย Group Query Attention)
- Multi-head latent attention
- Deep-seek sparse attention
เเละจะได้เเทรกเนื้อหาที่หลายโมเดลปัจจุบันใช้กันคือ Mix of Expert ( จริงๆอยู่ใน Feed forward เเต่หาที่ลงไม่ได้เลยมาไว้ในนี้)
