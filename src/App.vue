<template>
  <div id="app">
    <Menus refresh debug />
    <Panel debug :script-path="['./test1', './test2/script.jsx']">
      <Wrapper>
        <Button-Group>
          <Button block evalScript="test1Func()">Test 1</Button>
          <Button block evalScript="test2Func()">Test 2</Button>
        </Button-Group>
      </Wrapper>
    </Panel>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
