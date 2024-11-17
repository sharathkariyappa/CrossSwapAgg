<template>
    <section>
        <div class="app_width">
            <footer>
                <nav class="pages">
                    <a href="_" target="_blank">
                        <button>X (Twitter)</button>
                    </a>
                    <a href="" target="_blank">
                        <button>GitHub</button>
                    </a>
                </nav>

                <div class="featured">
                    <p>Developed by <a href="" target="_blank">Blockeam.</a></p>
                </div>
            </footer>
        </div>
    </section>
</template>

<style scoped>
section {
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
}

footer {
    height: 60px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.pages {
    display: flex;
    align-items: center;
    gap: 10px;
}

.pages button {
    color: var(--tx-dimmed);
    font-size: 14px;
    font-weight: 500;
    padding: 4px 10px;
    border-radius: 12px;
    background: none;
    cursor: pointer;
}

.pages button:hover {
    color: var(--tx-normal);
}

.featured p {
    font-size: 14px;
    font-weight: 500;
    color: var(--tx-semi);
}

.featured p a {
    color: var(--primary-light);
}

@media screen and (max-width: 800px) {
    footer {
        height: 40px;
    }

    .pages {
        gap: 4px;
    }

    .pages button {
        font-size: 12px;
        padding: 4px 6px;
    }

    .featured p {
        font-size: 12px;
    }
}
</style>