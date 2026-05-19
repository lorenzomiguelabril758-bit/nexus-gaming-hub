async function searchCharacter() {
    const userInput = document.getElementById("charInput").value.trim();
    const resultDiv = document.getElementById("resultDisplay");

    if (!userInput) {
        resultDiv.innerHTML = `<p style="color:#ff3333; margin-top:20px;">⚠️ Type a hero name!</p>`;
        return;
    }

    resultDiv.innerHTML = `<p style="color:#00ffcc; margin-top:20px;">🤖 AI is analyzing ${userInput}...</p>`;

    try {
        const response = await fetch("https://ai-gaming-database.com", {
            method: "POST",
            headers: { "Content-Type": "application/json" },
            body: JSON.stringify({ hero: userInput })
        });
        const data = await response.json();
        resultDiv.innerHTML = `
            <div style="background:#222; border:1px solid #00ffcc; border-radius:8px; padding:20px; margin-top:20px; display:inline-block; text-align:left; width:80%; max-width:400px;">
                <h3 style="color:#00ffcc; margin-top:0;">🤖 AI Meta: ${userInput}</h3>
                <p><strong>⚔️ Build:</strong> ${data.optimalBuild}</p>
                <p><strong>💡 Strategy:</strong> ${data.strategy}</p>
            </div>
        `;
    } catch (error) {
        resultDiv.innerHTML = `<p style="color:#ff3333; margin-top:20px;">⚠️ Server simulation active! Try "Ling" or "Fanny".</p>`;
    }
}
