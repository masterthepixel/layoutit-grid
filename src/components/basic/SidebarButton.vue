<template>
  <button>
    <slot />
  </button>
</template>

<style scoped lang="scss">
button {
  width: 100%;
  border: 0;
  cursor: pointer;
  height: 1.875rem;
  border-radius: 30px;
  font-size: 1rem;
  min-height: 2.188em;
  min-width: 2.188em;
  margin-bottom: 0.626em;
  padding: 0.313em 9px;

  color: #fff;
  background: var(--color-add);
  &.active {
    background: #27ae60;
  }
  &:hover {
    background: var(--color-add-active);
  }
}
</style>
