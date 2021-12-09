<template>
  <div class="app-container">
    <div style="margin-bottom:15px;">
      <label class="label">玩家ID：
        <input v-model.number="setPlayerId" name="playerId">
      </label>
    </div>
    <div style="margin-bottom:15px;">
      {{ '玩家名字：' }}: {{ 'player' }}
    </div>
    <div>
      <el-button type="primary" @click="queryInfo(playerId)">
        查询
      </el-button>
    </div>
  </div>
</template>

<script>

export default {
  data() {
    return {
      setPlayerId: 100110001
    }
  },
  methods: {
    queryInfo(playerId) {

    }
  }
}
</script>
