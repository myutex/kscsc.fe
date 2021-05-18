<template>
  <header>
    <div class="container mx-auto h-full flex items-center justify-between">
      <h1>
        <NuxtLink to="/">
          <img
            src="../static/kscsc-logo.jpeg"
            alt="한국중소기업지원협동조합 로고"
          />
        </NuxtLink>
      </h1>
      <ul>
        <li>
          <NuxtLink to="/">조합소개</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/">소식</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/">세무지원</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/">노무지원</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/">법률지원</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/">상담신청</NuxtLink>
        </li>
      </ul>
      <div>
        <NuxtLink class="profile-btn inline-block text-center" to="/">
          내정보
        </NuxtLink>
        <NuxtLink class="login-btn inline-block text-center" to="/">
          로그인
        </NuxtLink>
      </div>
    </div>
  </header>
</template>

<script>
export default {}
</script>

<style scoped lang="scss">
header {
  height: 80px;

  div.container {
    h1 > a {
      display: block;
      width: 218px;
      height: 45px;
    }

    ul {
      li {
        margin: 0 20px;

        a {
          font-weight: 700;
          color: #1c1f5b;
        }
      }
    }

    > div {
      a {
        font-weight: 700;
        vertical-align: bottom;
      }
      a.profile-btn {
        width: 80px;
        height: 40px;
        margin-right: 20px;
        border: 2px solid #418eff;
        color: #418eff;
        line-height: 40px;
      }
      a.login-btn {
        width: 127px;
        height: 40px;
        background-color: #418eff;
        color: #fff;
        line-height: 40px;
      }
    }
  }
}
</style>
