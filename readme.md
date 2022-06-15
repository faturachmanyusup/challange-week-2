<h1>Buat server menggunakan express js</h1>

<h2>ENDPOINTS</h2>

<h3>Items</h3>
<ul>
  <li>
    <h5>ENDPOINT: /items</h5>
    <h5>method: GET</h5> 
    <h5>Response: [ items ]</h5>
  </li>
  <li>
    <h5>ENDPOINT: /items/:id</h5>
    <h5>method: GET</h5> 
    <h5>Response: { message: "Berhasil mendapatkan item dengan id <i>#request_body</i>" }</h5>
  </li>
  <li>
    <h5>ENDPOINT: /items</h5>
    <h5>method: POST</h5> 
    <h5>Response: { message: "Berhasil menambahkan item dengan nama <i>#request_body</i>" }</h5> 
  </li>
  <li>
    <h5>ENDPOINT: /items</h5>
    <h5>method: PUT</h5> 
    <h5>Response: { message: "Berhasil mengubah item dengan id <i>#request_body</i>" }</h5> 
  </li>
  <li>
    <h5>ENDPOINT: /items</h5>
    <h5>method: DELETE</h5> 
    <h5>Response: { message: "Berhasil menghapus item dengan id <i>#request_body</i>" }</h5> 
  </li>
</ul>

<h3>Orders</h3>
<ul>
  <li>
    <h5>ENDPOINT: /orders</h5>
    <h5>method: GET</h5> 
    <h5>Response: [ orders ]</h5>
  </li>
  <li>
    <h5>ENDPOINT: /orders/:id</h5>
    <h5>method: GET</h5> 
    <h5>Response: { message: "Berhasil mendapatkan item dengan id <i>#request_body</i>" }</h5>
  </li>
  <li>
    <h5>ENDPOINT: /orders</h5>
    <h5>method: POST</h5> 
    <h5>Response: { message: "Berhasil menambahkan item dengan nama <i>#request_body</i>" }</h5> 
  </li>
  <li>
    <h5>ENDPOINT: /orders</h5>
    <h5>method: PUT</h5> 
    <h5>Response: { message: "Berhasil mengubah item dengan id <i>#request_body</i>" }</h5> 
  </li>
  <li>
    <h5>ENDPOINT: /orders</h5>
    <h5>method: DELETE</h5> 
    <h5>Response: { message: "Berhasil menghapus item dengan id <i>#request_body</i>" }</h5> 
  </li>
</ul>

<h3>Users</h3>
<ul>
  <li>
    <h5>ENDPOINT: /users/login</h5>
    <h5>method: GET</h5> 
    <h5>Response: { message: "Berhasil login." }</h5> 
  </li>
  <li>
    <h5>ENDPOINT: /users/register</h5>
    <h5>method: POST</h5> 
    <h5>Response: { message: "Berhasil mendaftarkan user baru." }</h5> 
  </li>
</ul>