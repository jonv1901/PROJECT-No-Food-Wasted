#  **Create Post**
post name or restaurant name:

 <input type="text" id="name" name="name"/>

 pickup adress:

<input type="text" id="address" name="name"/>

Description:

<input type="text" id="description" name="name"/>

<p style="margin-top:25px"><a onclick="createFakePost()"><img src="images/submit-button-png-25801.png" width="250px" height="75px"></a>

<script>
    const createFakePost = () => {
        const name = document.getElementById('name').value;
        const description = document.getElementById('description').value;

        window.location.href = `https://jonv1901.github.io/PROJECT-No-Food-Wasted/corkboard?postTitle=${name}&postDesc=${description}`;
    }
</script>