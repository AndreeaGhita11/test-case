# Test Case Samples

Here are some test cases on an online store.

---

### Test case 1:
**Description:**
Creating a new user on the site.

**Steps to reproduce:**
1. Go to www.zoopoint.ro
2. Click to “Intra in cont” button
3. Click to “Inregistreaza-te” button 
4. Insert data in all required fields
5. Tick all required fields
5. Click to “Inregistreaza-te” button

**Expect result:**
A new user should be created. User should receive an email with confirmation. 

---

### Test case 2:
**Description:** Check if login works correctly when a person uses a correct user/password.

**Steps to reproduce:**
1. Go to www.zoopoint.ro
2. Click to “Intra in cont” button
3. Add a correct user/password.
4. Press “Intra in cont” button.

**Expected result:**
User should be able to login and is taken to his profile page.

**Test data:**
User: ghita.andreea@google.com
Password: 123456

--- 

### Test case 3:
**Description:**
Test login with correct user and wrong password.

**Steps to reproduce:**
1. Go to www.zoopoint.ro/inregistrare
2. Add a correct user and wrong password
3. Press “Intra in cont” button

**Expected result:**
User shouldn’t be able to login.

---

### Test case 4:
**Description:**
Check if forgot my password functionallity works as expected and email with reset password link is sent.
**Steps to reproduce:**
1. Go to www.zoopoint.ro/inregistrare
2. Click to “Ai uitat parola?”
3. Add an email adrees
4. Press “Trimite” button 

**Expected resut:**
User should recive an email with a reset password link, and this link should allow the user to create a new password.

---

### Test case 5:
**Description:**
Add one product to wishlist.'

**Steps to reproduce:**
1. Go to www.zoopoint.ro/caini
2. Click to the first product you will see on this page
3. Click to “Adauga la Favorite” button

**Expected result:**
Product should be saved in wishlist.

---

### Test case 6:
**Description:**
Remove one product from wishlist.
**Steps to reproduce:**
1. Go to www.zoopoint.ro/contul-meu
2. Click to “Produse salvate”
3. Click to delete button 

**Expected result:**
The product you’ll chose, should be remeoved from wishlist. 

---

### Test case 7:
**Description:**
Add a product from to wishlist to shopping cart.
**Steps to reproduce:**
1. Go to www.zoopoint.ro/wishlist
2. Click to “Adauga in cos” button from one product

**Expected results:**
The product should be move from wishlist to shopping cart.

---

### Test case 8:
**Description**
Add a product to shopping cart.

**Steps to reproduce:**
1. Go to www.zoopoint.ro/caini
2. Click to “Hrana uscata caini” link, on the left menu 
3. Click to “Vezi variante” button for first product you’ll see 
4. Choose weight from product
5. Click to “Adauga in cos” button

**Expected result:**
The product should be added on shopping cart with selected weight.