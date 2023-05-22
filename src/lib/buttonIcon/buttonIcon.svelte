<style>
button {
  padding: 10px 20px;
  font-size: 16px;
  font-weight: bold;
  text-align: center;
  text-decoration: none;
  color: #4CAF50;
  background-color: transparent;
  transition: background-color 0.3s ease;
  cursor: pointer;
  border: 0;
}

/* Estilos cuando se pasa el cursor sobre el botón */
button:hover {
  background-color: transparent;
  color: #4CAF50;
}

/* Estilos cuando se presiona el botón */
button:active {
  background-color: transparent;
  color: #3e8e41;
}


</style>


 <button ><slot></slot></button>