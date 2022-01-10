<template>

    <div
        class="entry-container mb-3 pointer p-2"
        @click="$router.push({name: 'entry', params: {id: 10}})"
    >
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">15</span>
            <span class="mx-1 fs-5">Julio</span>
            <span class="mx-2 fw-light">2021, Jueves</span>
        </div>
        <div class="entry-description">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Obcaecati aut voluptatibus reiciendis vitae harum! At magni facilis deserunt ullam sunt molestias provident? Fugit debitis assumenda ipsum obcaecati atque. Ducimus, quam.
            Quo, nam, optio expedita hic voluptatum vel illo iste dolorum velit distinctio exercitationem quibusdam repellendus facere nulla. Exercitationem possimus aspernatur distinctio quisquam perferendis qui nisi ex enim, fugiat, repudiandae sapiente?
            Eligendi molestiae commodi quas architecto iste eius sed perspiciatis officia necessitatibus quos veniam magnam perferendis quam, harum minima magni corporis quasi dolor ipsam ad tempore. Accusantium error dicta mollitia architecto?
            Amet expedita doloribus maiores vero dolore voluptatibus, rerum reiciendis similique fugit. Sequi id enim molestias deserunt amet consequatur, vel et cupiditate.
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease;

    &:hover {
        background-color: lighten($color: grey, $amount: 45);
    }
    .entry-description {
        font-size: 12px;
    }
}

</style>