<template>
    <Page>
        <ActionBar title="Welcome to NativeScript-Vue!"/>
        <GridLayout columns="*" rows="*">
            <WebViewExt row="0" src="https://www.bbc.com" debugMode="true"></WebViewExt>
        </GridLayout>
    </Page>
</template>

<script>
  import { WebViewExt } from '@nota/nativescript-webview-ext'

  export default {
    data() {
      return {
        msg: 'Hello World!'
      }
    }
  }
</script>

<style scoped>
    ActionBar {
        background-color: #53ba82;
        color: #ffffff;
    }

    .message {
        vertical-align: center;
        text-align: center;
        font-size: 20;
        color: #333333;
    }
</style>
