# Code_demo
This is my First Git Repository.
Author_Ashutosh Kumar Kannaujiya
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ashutosh Kumar Kannaujiya | Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
            font-family: Arial, sans-serif;
        }

        body {
            background: #0f172a;
            color: white;
            line-height: 1.6;
        }

        /* Navbar */
        header {
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            background: #020617;
            padding: 18px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #38bdf8;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 25px;
            font-size: 16px;
        }

        nav a:hover {
            color: #38bdf8;
        }

        /* Common */
        section {
            padding: 100px 8%;
        }

        .title {
            text-align: center;
            font-size: 35px;
            margin-bottom: 45px;
            color: #38bdf8;
        }

        /* Home */
        #home {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding-top: 120px;
        }

        .home-content h1 {
            font-size: 50px;
            margin-bottom: 15px;
        }

        .home-content h1 span {
            color: #38bdf8;
        }

        .home-content h2 {
            font-size: 25px;
            color: #cbd5e1;
            margin-bottom: 20px;
        }

        .home-content p {
            max-width: 650px;
            margin: auto;
            color: #94a3b8;
        }

        .btn {
            display: inline-block;
            margin-top: 30px;
            padding: 12px 25px;
            background: #38bdf8;
            color: #020617;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
        }

        .btn:hover {
            background: white;
        }

        /* About */
        .about {
            max-width: 850px;
            margin: auto;
            text-align: center;
            color: #cbd5e1;
            font-size: 18px;
        }

        /* Skills */
        .skills-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }

        .skill-card {
            background: #1e293b;
            padding: 35px 20px;
            text-align: center;
            border-radius: 15px;
            border: 1px solid #334155;
            transition: 0.3s;
        }

        .skill-card:hover {
            transform: translateY(-8px);
            border-color: #38bdf8;
        }

        .skill-card h3 {
            color: #38bdf8;
            margin-bottom: 10px;
        }

        /* Projects */
        .projects-container {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 25px;
        }

        .project-card {
            background: #1e293b;
            padding: 30px;
            border-radius: 15px;
            border: 1px solid #334155;
        }

        .project-card h3 {
            color: #38bdf8;
            margin-bottom: 12px;
        }

        .project-card p {
            color: #cbd5e1;
        }

        /* Education */
        .education {
            text-align: center;
        }

        .education-box {
            max-width: 750px;
            margin: auto;
            background: #1e293b;
            padding: 30px;
            border-radius: 15px;
        }

        .education-box h3 {
            color: #38bdf8;
        }
