-- SEQUENCE: lehner_02272.rooms_id_seq

-- DROP SEQUENCE IF EXISTS lehner_02272.rooms_id_seq;

CREATE SEQUENCE IF NOT EXISTS lehner_02272.rooms_id_seq
    INCREMENT 1
    START 1
    MINVALUE 1
    MAXVALUE 2147483647
    CACHE 1;

ALTER SEQUENCE lehner_02272.rooms_id_seq
    OWNED BY lehner_02272.rooms.id;

ALTER SEQUENCE lehner_02272.rooms_id_seq
    OWNER TO student;