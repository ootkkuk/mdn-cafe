<template>
  <layout-wrapper>
    <layout-visual
      title="Information"
      :height="40"
      visual="visual-information"
    />
    <div class="w-full md:max-w-3xl mx-auto pt-20">
      <div class="mb-20">
        <layout-information-list
          v-for="(item, index) in items"
          :id="item.id"
          :key="index"
          :date="item.date"
          :title="item.title"
        />
      </div>
    </div>
  </layout-wrapper>
</template>

<script>
import axios from 'axios';
export default {
  async asyncData({ $config }) {
    const { data } = await axios.get(
      `${$config.apiUrl}news`,
      { headers: { 'X-MICROCMS-API-KEY': $config.apiKey }}
    );
    return {
      items: data.contents
    }
  }
}
</script>