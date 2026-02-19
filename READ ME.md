# **MongoDB First Day Practice Task**
-
**Part 1: Setup & Exploration 🌱**

1. Install MongoDB Community Edition on your computer (or use MongoDB Atlas free tier cloud)
2. Start the MongoDB server
3. Open MongoDB Shell (mongosh)
4. Type show dbs to see existing databases

**Part 2: Create Your First Database 📚**

1. Create a database called "student_life"
   · Hint: Use use student_life
2. Verify you're using the right database with db

**Part 3: Create a Simple Collection 📝**

1. Create a collection called "notes"
2. Insert ONE note document with:
   · A title
   · Some content
   · Today's date
   Example format (but make it your own!):
   ```javascript
   {
     "title": "First MongoDB Notes",
     "content": "MongoDB stores data in documents",
     "created_date": new Date()
   }
   ```

**Part 4: Basic Queries 🔍**

1. Find all notes: db.notes.find()
2. Find your note specifically by title
3. Count how many notes you have


**Success Criteria:**

✅ You can see your database when typing show dbs
✅ Your "notes" collection has at least 3 documents
✅ You can retrieve all notes with a query
