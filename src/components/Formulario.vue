<template>
  <div class="container">
    <form>
      <div>
        <label>Moneda Nacional:</label>
        <select required>
          <option value="" disabled selected>Selecciona la Moneda ....</option>
          <option>MXN</option>
          <option>USD</option>
          <option>EUR</option>
        </select>
      </div>
      <div>
        <label>Criptomoneda:</label>
        <select required>
          <option value="" disabled selected>
            Selecciona la Criptomoneda ....
          </option>
          <option>BTC</option>
          <option>ETH</option>
          <option>LTC</option>
        </select>
      </div>
      <div>
        <button type="submit">Cotizar</button>
      </div>
    </form>
  </div>
</template>

<script>
export default {};
</script>
