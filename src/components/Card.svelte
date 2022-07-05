<script>
  import Comments from './Comments.svelte'
</script>

<div class="Card">
  <div class="Card-container">
    <div class="Card-header">
      <div class="Card-user">
        <img src="https://images.pexels.com/photos/1805164/pexels-photo-1805164.jpeg?auto=compress&cs=tinysrgb&w=1600" alt="">
        <h2>
          Doggyloco
          <span>Queretaro, Mexico</span>
        </h2>
      </div>
      <div class="Card-settings">
        <i class="fa-solid fa-ellipsis-h" />
      </div>
    </div>
    <div class="Card-photo">
      <figure>
        <img src="https://images.pexels.com/photos/1805164/pexels-photo-1805164.jpeg?auto=compress&cs=tinysrgb&w=1600" alt="">
      </figure>
    </div>
    <div class="Card-icons">
      <div class="Card-icons-first">
        <i class="fa-solid fa-heart" />
        <i class="fa-solid fa-paper-plane" />
      </div>
      <div class="Card-icons-second">
        <i class="fa-solid fa-bookmark" />
      </div>
    </div>
    <div class="Card-description">
      <h3>Doggyloco</h3>
      <span>Hello * woof woof *</span>
    </div>
    <Comments />
  </div>
</div>