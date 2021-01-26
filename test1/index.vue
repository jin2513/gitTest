<template>
  <div id="container" class="login-page">
    <div class="login">
      <div class="section">
        <div class="tit">
        </div>
        <div class="fields">
          <ul>
            <li><input ref="userId" type="text" v-model.trim="userId" class="comText" placeholder="아이디를 입력해주세요" @keyup.enter="login" /></li>
            <li><input ref="userPw" type="password" v-model.trim="userPw" class="comText" placeholder="비밀번호를 입력해주세요" autocomplete="off" @keyup.enter="login" /></li>
            <li>test</li>
            <li>aaaaa</li>
          </ul>
          <button type="submit" class="btLogin" @click.prevent="login">LOGIN</button>
        </div>
      </div>
    </div>
  </div>
</template>
