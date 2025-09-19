# Quiz_Convert_List
Quiz Convert to Array &amp; List Key-Value Ruby 

จงพิจารณาโค้ดด้านล่างนี้เพื่อตอบคำถาม

```ruby
text = "ruby"
letters = text.chars
info = { language: letters.join.upcase, length: letters.length }
puts info[:language]
```

A.โค้ดด้านล่างนี้ทำให้เกิดอะไรขึ้นกับ text 
```ruby
text.chars
```

<details>
  <summary>Answer A</summary>
  
`text.chars` จะเปลี่ยน string `"ruby"` ให้กลายเป็น array ของตัวอักษรแต่ละตัว → `["r", "u", "b", "y"]` 

</details>

B.โค้ดทั้ง 2 ตัวนี้เมื่อถูกเรียกใช้งานจะทำให้เกิดอะไรขึ้น

```ruby
{ language: letters.join.upcase}
{ length: letters.length }
```
<details>
  <summary>Answer B</summary>

  `{ language: letters.join.upcase }` ได้ `"RUBY"`  
`{ length: letters.length }` ได้ `4`

โดยมีหลักการทำงานดังนี้

 `{ language: letters.join.upcase }` สร้าง hash ที่รวมตัวอักษรแล้วแปลงเป็นตัวพิมพ์ใหญ่  
 `{ length: letters.length }` สร้าง hash ที่นับจำนวนตัวอักษรใน array  

</details>

C.โค้ดด้านล่างให้ผลลัพธ์เป็นอะไร?

```ruby
puts info[:language]
```

<details>
  <summary>Answer C</summary>
  
```ruby
"RUBY"
```

เพราะ

 `puts info[:language]` → ดึงค่าจาก key `:language` แล้วแสดงผล → `"RUBY"`

</details>

## จัดทำโดย : 
 
 นายมนัสวี ลูกเหล็ม 660710094



