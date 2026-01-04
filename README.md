# My Minimalistic Blog

A clean, fast, and simple blog template.

## Structure

- `index.html`: The main page listing your posts.
- `style.css`: The styling for the entire blog.
- `posts/`: Directory containing individual blog posts.

## How to add a new post

1. **Create a new file**: 
   Copy `posts/hello-world.html` and rename it (e.g., `posts/my-new-post.html`).

2. **Edit the content**: 
   Open the new file and change the title, date, and content HTML.

3. **Link it**: 
   Open `index.html` and add a new list item to the `<ul>` with the class `post-list`:

   ```html
   <li class="post-item">
       <span class="post-date">Your Date</span>
       <h2 class="post-title"><a href="posts/my-new-post.html">Your Post Title</a></h2>
       <p class="post-excerpt">A short summary of your post...</p>
       <a href="posts/my-new-post.html" class="read-more">Read article &rarr;</a>
   </li>
   ```

## Hosting options

This blog is hosted on:


