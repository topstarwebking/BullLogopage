<script>
</script>

<div class="profile-page">
  <section class="logo">
    <img src="./logo.png" alt="ChI NBA LOGO">
  </section>
  <section class="header-title">WHAT IS YOUR ADDRESS?</section>
  <section class="desc">We will ship your prize to you shortly</section>
  <section class="input-group">
    <div class="street-part">
      <div></div>
      <input class="street-input" placeholder="Street"/>
    </div>
    <div class="detail-info">
      <input type="text" placeholder="City" class="input-item">
      <input type="text"  placeholder="State" class="input-item">
    </div>
    <div class="detail-info">
      <input type="text" placeholder="Country" class="input-item">
      <input type="text" placeholder="Postal Code" class="input-item">
    </div>
  </section>
  <section>
    <button class="btn-save">SAVE</button>
  </section>
</div>

<style lang="scss">
  *, *::after, *::before {
    box-sizing: border-box;
  }

  input::placeholder {
    font-family: SFUIDisplay;
    font-size: 15px;
    font-weight: 300;
    font-stretch: normal;
    font-style: normal;
    line-height: normal;
    letter-spacing: normal;
    color: #000;
  }

  .input-group {
    width: 100%;
    padding: 0 30px 0 28px;
  }

  .input-item {
    height: 40px;
    border-radius: 30px;
    background-color: #fff;
    min-width: 0;
    padding: 11px 7.9px 11px 20px;
    flex: 1;
    &:focus {
      outline: 0;
    }
  }

  .input-item:first-child {
    margin-right: 15px;
  }

  .input-item:last-child {
    margin-left: 15px;
  }
  .street-part {
    height: 40px;
    border-radius: 30px;
    margin: 16px 0 12px 0;
    padding: 9px 11px 9px 20px;
    background-color: #fff;
    display: flex;
    width: 100%;
    div {
      width: 30px;
      height: 22px;
      
    }
    input {
      margin: 0;
      border: none;
      width: calc(100% - 30px);
      &:focus {
        outline: 0;
      }
    }
  }

  .btn-save {
    margin: 59px 98px 153px 97px;
    padding: 12px 67px 11px 68px;
    box-shadow: 0 5px 6px 0 rgba(0, 0, 0, 0.22);
    background-color: #fff;
    font-family: SFUIDisplay;
    font-size: 16px;
    font-weight: 900;
    font-stretch: normal;
    font-style: normal;
    line-height: normal;
    letter-spacing: 0.78px;
    text-align: center;
    color: #161616;
  }

  .profile-page {
    background-color: #000;
    padding: 88px 0;
    text-align: center;
    width: 100%;
    span {
      font-weight: bold;
    }
  }

  .logo {
    img {
      width: 90px;
      height: 81px;
    }
  }
  .detail-info {
    width: 100%;
    display: flex;
    justify-content: center;
  }

  .header-title {
    text-align: left;
    margin: 12px 28px;
    font-family: SFUIDisplay;
    font-size: 42px;
    font-weight: 900;
    font-stretch: normal;
    font-style: normal;
    line-height: 1.07;
    letter-spacing: normal;
    color: #fff;
  }

  .desc {
    text-align: left;
    margin: 12px 30px 16px 31px;
    font-family: SFUIDisplay;
    font-size: 14px;
    font-weight: 500;
    font-stretch: normal;
    font-style: normal;
    line-height: 1.43;
    letter-spacing: 0.5px;
    color: #fff;
  }

</style>
