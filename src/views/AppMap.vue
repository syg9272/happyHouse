<template>
  <kakao-map></kakao-map>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import KakaoMap from "@/components/map/KakaoMap.vue";

export default {
  name: "AppMap",
  data() {
    return {
      location: null,
    };
  },
  components: {
    KakaoMap,
  },
  methods: {
    findLocation() {},
  },
};
</script>

<style>
main .map {
  /* background-image: url("https://s3-alpha-sig.figma.com/img/8393/7f4b/ea706076cd76503e7219376269e4062a?Expires=1668988800&Signature=etJY9NAIbEXSYkFN-EZnnUxEoEcbXJUVNvZiMhe5bKbbP6PTam2-kyJuSvUseAIULwbRSkvfVPi1EWtdacHYBIWfm~8-YH-Wp13it9YN77cuMGylAa-w1bPvPC0ltOfzcOHBwEkrQrTu-CotTJM0DIJTjhA490VmaWdJwAMKdLSBmMfTkvAh8xxS6e4qr8iR~7bn9-fYtAs4byS~ua2HeTXCLkPKV8eG6AvAQ-SKbG~W1m6vy12wAsTxgt~N4zDzusYVKy-e7VzM0oBQMrHmrv4pvVFSxsFFA5HyU5l4Yehx-4kvElY8hq6l0udQ~m218dCH9wOU3I6s5UyqIrldfw__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA"); */
  position: absolute;
  overflow: hidden;
  width: 100%;
  height: 86%;
  /* background-color: blanchedalmond; */
}

/* main .map .location-search {
  background-image: url("@/assets/img/search.png");
  background-position: 410px;
  background-repeat: no-repeat;
  cursor: pointer;
  padding: 0 30px;
  width: 457px;
  height: 50px;
  position: relative;
  font-size: 16px;
  top: 20px;
  left: 34px;
  border-radius: 10px;
  border: 0.3px solid rgba(0, 0, 0, 0.5);
  box-shadow: 4px 4px 4px 0px rgba(0, 0, 0, 0.25);
}

main .map .location-search:focus {
  outline: none;
  border-radius: 10px 10px 0 0;
}

main .map .location-search:focus + .map-search {
  visibility: visible;
}

main .map .map-search {
  width: 457px;
  position: relative;
  visibility: hidden;
  top: 20px;
  left: 34px;
  padding: 15px 20px;
  background-color: white;
  border: 0.3px solid rgba(0, 0, 0, 0.5);
  box-shadow: 4px 4px 4px 0px rgba(0, 0, 0, 0.25);
  border-radius: 0 0 10px 10px;
}

main .map .map-search > div {
  display: flex;
  flex-direction: row;
  align-items: center;
}

main .map .map-search > div > * {
  margin: 5px 10px;
}

main .map .map-search > div > .location-name {
  color: #a1a1a1;
  font-size: small;
}

main .map img {
  width: 22px;
  height: 22px;
} */
</style>
