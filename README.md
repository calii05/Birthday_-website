 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Letters for You</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f2f6ff;
      margin: 0;
      padding: 30px 10px;
    }
    h1 {
      text-align: center;
      font-size: 2.5rem;
      color: #333;
      margin-bottom: 5px;
    }
    .subtitle {
      text-align: center;
      font-size: 1rem;
      color: #777;
      margin-bottom: 30px;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .card {
      background: #fff;
      padding: 20px;
      border-radius: 14px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.06);
      width: 280px;
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
    }
    .tag {
      padding: 4px 10px;
      font-size: 0.75rem;
      border-radius: 20px;
      background-color: #eee;
      font-weight: 600;
      text-transform: uppercase;
    }
    .tag.love { background-color: #ffe0e0; color: #b60000; }
    .tag.health { background-color: #e0fff4; color: #007f5f; }
    .tag.career { background-color: #e0e6ff; color: #1e40af; }
    .tag.you { background-color: #f2e0ff; color: #6a00b6; }
    p {
      font-size: 0.95rem;
      color: #444;
    }
  </style>
</head>
<body>

  <h1>Letters</h1>
  <p class="subtitle">Categorized letters for you.</p>

  <div class="container">
    <div class="card">
      <div class="tags">
        <span class="tag love">LOVE</span>
        <span class="tag you">YOU</span>
      </div>
      <p>Thank you for being patient with me every time na may toyo ako, thank you at andyan ka palagi.</p>
    </div>

    <div class="card">
      <div class="tags">
        <span class="tag career">CAREER</span>
      </div>
      <p>Nakakatakot na baka balang araw mawala tayo sa isa't isa kasi di na same ang pangarap natin. Pero sana sa dulo, ikaw pa rin.</p>
    </div>

    <div class="card">
      <div class="tags">
        <span class="tag you">YOU</span>
        <span class="tag health">HEALTH</span>
      </div>
      <p>Hindi ako natatakot sa kamatayan noon, pero nung makita kitang umiyak sa sakit, natakot ako bigla. Ayokong mawala ka.</p>
    </div>

    <div class="card">
      <div class="tags">
        <span class="tag love">LOVE</span>
      </div>
      <p>I want to spend the rest of my life with you.</p>
    </div>
  </div>

</body>
</html>
