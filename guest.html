<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1.0" />
  <title>Guest Entry</title>
  <style>
    body {
      background: linear-gradient(135deg,#0f172a,#1e1b4b);
      color: #e6eef8;
      font-family: "Inter", sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 40px;
      min-height: 100vh;
    }
    h1 {
      background: linear-gradient(90deg,#7c3aed,#06b6d4);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    table {
      border-collapse: collapse;
      margin-top: 20px;
      width: 80%;
    }
    th, td {
      border: 1px solid rgba(255,255,255,0.1);
      padding: 10px;
      text-align: center;
    }
    input {
      background: rgba(255,255,255,0.1);
      border: none;
      color: white;
      padding: 8px;
      border-radius: 6px;
    }
    button {
      background: linear-gradient(90deg,#7c3aed,#06b6d4);
      border: none;
      color: white;
      padding: 10px 16px;
      border-radius: 8px;
      cursor: pointer;
      font-weight: 600;
      margin-top: 10px;
    }
    button:hover { opacity: 0.9; }
  </style>
</head>
<body>
  <h1>Guest Entry Portal</h1>

  <table id="guestTable">
    <tr><th>Name</th><th>Priority</th></tr>
    <tr>
      <td><input type="text" placeholder="Enter name" /></td>
      <td><input type="number" placeholder="Priority" /></td>
    </tr>
  </table>
  <button onclick="addRow()">Add More</button>
  <button onclick="saveGuests()">Next →</button>

  <script>
    function addRow(){
      const table = document.getElementById("guestTable");
      const row = document.createElement("tr");
      row.innerHTML = `<td><input type="text" placeholder="Enter name" /></td>
                       <td><input type="number" placeholder="Priority" /></td>`;
      table.appendChild(row);
    }

    function saveGuests(){
      const rows = document.querySelectorAll("#guestTable tr");
      const guests = [];
      rows.forEach((r,i)=>{
        if(i===0) return;
        const name = r.querySelectorAll("input")[0].value.trim();
        const priority = parseInt(r.querySelectorAll("input")[1].value);
        if(name) guests.push({name,priority:priority||0});
      });
      localStorage.setItem("guests", JSON.stringify(guests));
      window.location.href = "algorithm.html";
    }
  </script>
</body>
</html>
