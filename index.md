<div class="two-column">
  <div class="column">
    <!-- Left column content -->
    {{ content }}
  </div>

  <div class="column">
    <!-- Right column content -->
    <!-- Maybe your Projects or About section -->
  </div>
</div>

<style>
.two-column {
  display: flex;
  gap: 40px;
}

.column {
  flex: 1;
}
@media (max-width: 768px) {
  .two-column {
    flex-direction: column;
  }
}
</style>
