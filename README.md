# LEi
wear elegance that tells your story
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  padding: 20px;
  background-color: #f4f4f4;
}

header {
  text-align: center;
  margin-bottom: 20px;
}

#cart-info {
  text-align: right;
}

#cart-button {
  padding: 10px;
  background-color: #007bff;
  color: white;
  border: none;
  cursor: pointer;
}

#cart-button:hover {
  background-color: #0056b3;
}

#product-list {
  display: flex;
  justify-content: space-around;
}

.product {
  text-align: center;
  background-color: white;
  border-radius: 10px;
  padding: 20px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  width: 200px;
}

.product img {
  width: 100%;
  height: auto;
}

.add-to-cart {
  background-color: #28a745;
  color: white;
  border: none;
  padding: 10px;
  cursor: pointer;
  margin-top: 10px;
}

.add-to-cart:hover {
  background-color: #218838;
}

#cart-modal {
  display: none;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
  justify-content: center;
  align-items: center;
}

.modal-content {
  background-color: white;
  padding: 20px;
  border-radius: 10px;
  width: 300px;
  text-align: center;
}

button {
  margin: 10px 0;
}
